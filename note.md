# patch ELF

1. https://nixos.org/patchelf.html
2. patchelf --set-interpreter /my/lib/my-ld-linux.so.2 program
3. patchelf --set-rpath /opt/my-libs/lib:/foo/lib program
