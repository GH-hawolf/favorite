#### issue
- error while loading shared libraries: libpng12.so.0: cannot open shared object file: No such file or directory
- solution
    - [ref](https://github.com/tcoopman/image-webpack-loader/issues/95)
    - wget -q -O /tmp/libpng12.deb http://mirrors.kernel.org/ubuntu/pool/main/libp/libpng/libpng12-0_1.2.54-1ubuntu1_amd64.deb
    - sudo dpkg -i /tmp/libpng12.deb
    - rm /tmp/libpng12.deb
