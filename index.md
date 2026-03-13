---
layout: default
---


GemmiMol is a web-based macromolecular viewer focused on electron density.
It is a next-gen version of [UglygMol](https://uglymol.github.io/)

It makes models and e.den. maps easy to recognize, navigate and interpret --
for crystallographers.
It looks like [Coot](http://www2.mrc-lmb.cam.ac.uk/personal/pemsley/coot/)
and walks (mouse controls) like Coot.
But it's only a viewer. For situations when you want
a quick look without downloading the data and starting Coot.
For instance, when screening
[Dimple](http://ccp4.github.io/dimple/) results in a synchrotron.
Of course, for this to work, it needs to be integrated into a website
that provides the data access
(see the [FAQ](https://github.com/gemmimol/gemmimol/wiki) on how to do it).

Try it:

- [1MRU](1mru.html) (60kDa, 3Å),
  and in [dual view](dual.html) with PDB_REDO,
- [a blob](dimple_thaum.html#xyz=14,18,12&eye=80,71,-41&zoom=70)
  (Dimple result, thaumatin, 1.4Å),
- or any [local file or wwPDB entry](view/).


It also has a [reciprocal space spin-off](reciprocal.html?rlp=data/rlp.csv).

GemmiMol is a small (~3 KLOC) [project](https://github.com/gemmimol/gemmimol)
The [plan](https://github.com/gemmimol/gemmimol/blob/master/TODO.md)
is to keep it small and fast. But if you're missing some functionality,
it won't hurt if you get in touch --
use [Issues](https://github.com/gemmimol/gemmimol/issues)
or [email](mailto:wojdyr@gmail.com).

