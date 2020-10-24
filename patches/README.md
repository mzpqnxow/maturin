## Patches for ppc64le compatibility

This branch is already pre-patched, but the patch `.diff` in this directory is included anyway. Thanks to @programmerjake for providing the flags that disable features that require `ring`, which still has an open issue for ppc64le support associated with AES-GCM code [here](https://github.com/briansmith/ring/issues/389)
