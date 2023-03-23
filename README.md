A helper scripts to simplify alibuild recipes used by nicadist fork.

## generate-module
Simple script to create Modulefile. Supported parameters:
 | parameter | meaning |
 |-----------|---------|
 |--bin | will add $PKG_ROOT/bin to PATH |
 |--lib | will add $PKG_ROOT/lib to LD_LIBRARY_PATH |
 |--lib64 | will add $PKG_ROOT/lib64 to LD_LIBRARY_PATH |
 |--path | will fill $PKG_PATH where programs are placed (/path/sw/architecture). $PKG_ROOT=$PKG_PATH/PACKAGE_NAME |
 |--project=NAME | will put 'NAME' before Modulefile in description |
 |--root | will fill $PKG_ROOT variable even if no bin or lib(64) is present (header only recipes) |
