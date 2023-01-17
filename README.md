# libgiis

This is a header-only C++ library for en/decoding [GIIS](https://directreadout.sci.gsfc.nasa.gov/links/rsd_eosdb/PDF/ICD_Space_Ground_Aqua.pdf) formatted data, as used in the MODIS instrument of the Terra/Aqua satellite missions.
It can be used in combination with [libspp](https://github.com/ssloxford/libspp) to en/decode the complete Level 0 MODIS data packet format.
These files can be found at the NASA archives such as [LAADS DAAC](https://ladsweb.modaps.eosdis.nasa.gov/#level0-level1).

Also contained is `test.cpp`, a simple program to demonstrate usage of the library.
The library is used in the `sppinfo` CLI tool in the [libspp](https://github.com/ssloxford/libspp) repository, to provide information on MODIS data.

## Building

Dependencies:

* [libgetsetproxy](https://github.com/ssloxford/libgetsetproxy)

Building:

```
make
make install
```

## Thanks

Many thanks to [Jonathan Tanner](https://github.com/aDifferentJT) for his help in writing this library.
