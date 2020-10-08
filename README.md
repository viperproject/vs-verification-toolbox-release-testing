# vs-verification-toolbox-release-testing
This repository is intenionally left empty.
It's main purpose is to host several pre- and non-prereleases that can be used to test some features in the vs-verification-toolbox repository.

## Release Assets
The assets have been created as follows:
- small.bin: `head -c 10 < /dev/urandom > small.bin`
- medium.bin: `head -c 1000000 < /dev/urandom > medium.bin`
- large.bin: `head -c 10000000 < /dev/urandom > large.bin`
- small.zip: `zip small.zip small.bin`
- medium.zip: `zip medium.zip medium.bin`
- large.zip: `zip large.zip large.bin`

Note that each release uses newly generated `.bin` files. 
