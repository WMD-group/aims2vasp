aims2vasp
=========

Using Github for an internal utility script seems like overkill, but it's all good practice!

At the moment, this script will take the name of a basic geometry.in file for the FHI-aims quantum chemistry code, and writes out the atom positions and unit cell vectors in a suitable format for a VASP POSCAR file. This is useful for cross-checking DFT calculations, and for viewing relaxed structures.

The current development goal is to improve robustness in handling relaxation files which include additional information beyond basic geometry.

Work is dormant at the moment as the addition of geometry.in support to VESTA has provided a workaround.

Disclaimer
----------
This script is not affiliated with *FHI-aims*. Feel free to use it and build on it, but do so at your own risk.