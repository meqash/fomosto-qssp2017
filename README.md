# QSSP2017 (packaged as Fomosto backend)

Code for calculating complete synthetic seismograms of a spherical earth using
normal mode theory.

QSSP2017 has been written by Rongjiang Wang.

This is the newest version of the legacy code of QSSP.
New features are:
- dynamic memory allocation
- todo ...

Packaging has been done by Hannes Vasyura-Bathke.

## References

- Gilbert, F. and Backus, G.: Elastic-gravitational vibrations of a radially
  stratified sphere, in: Dynamics of Stratified Solids, edited by: Herrmann,
  G., American Society of Mechanical Engineers, New York, 82–95, 1968.
  Takeuchi, H., and M. Saito (1972). Seismic surface waves, in Methods in
  Computational Physics, vol. 11, Bolt, B. A. , Editor Academic Press, New
  York, 217- 295. 

- Wang, R., (1997), Tidal response of the solid earth, in Tidal Phenomena,
  edited by H. Wilhelm, W. Zürn and H.G. Wenzel, Lecture Notes in Earth
  Sciences, Vol. 66, pp. 27-57, Springer-Verlag, Berlin/Heidelberg, Germany,
  1997.

## Compile and install

```
autoreconf -i   # only if 'configure' script is missing
./configure
make
sudo make install
```
