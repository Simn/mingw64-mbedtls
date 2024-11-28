# mingw64-x86_64-mbedtls

Download the [release](https://github.com/Simn/mingw64-mbedtls/releases) corresponding to your platform into your Cygwin root install directory, and unpack it with `tar -xf [file]`.

## Building

To build the package, your cygwin installation must include cygport and cmake. Once all requirements are installed, open a cygwin terminal and run:

```sh
cygport mingw64-x86_64.cygport download
cygport mingw64-x86_64.cygport all
```

To test the package, you can unzip it into the root directory:

```sh
tar -C / -xvf mingw64-x86_64-mbedtls-*-1.noarch/dist/mingw64-x86_64-mbedtls/mingw64-x86_64-mbedtls-*-1.tar.xz
```

See [cygwin documentation](https://cygwin.com/packaging-contributors-guide.html) for more information.
