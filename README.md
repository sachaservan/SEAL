See [Microsoft SEAL 3.5.0](https://github.com/microsoft/SEAL/tree/3.5.0) for documentation. 
To build for use with [OnionPIR](https://github.com/mhmughees/Onion-PIR/blob/f318ef458fbdb1e063cb1bec3a5f89d89a6b654c/README.md), run:
```
git checkout 3.5.0
cmake . -DCMAKE_BUILD_TYPE=Release -DSEAL_USE_MSGSL=OFF -DSEAL_USE_ZLIB=OFF
make
sudo make install
```
