# Reviving the RcppOctave package (WIP)

Currently only tested with R 4.0.4 on Octave 5.2.0 on Ubuntu 20.04 LTS

## build

```
R CMD build --no-manual --no-build-vignettes RcppOctave
```

## install

```
sudo LD_PRELOAD=/usr/lib/x86_64-linux-gnu/liboctinterp.so:/usr/lib/x86_64-linux-gnu/liboctave.so R CMD INSTALL RcppOctave_0.20.tar.gz
```
