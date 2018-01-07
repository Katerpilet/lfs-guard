# lfs-guard
Scripts for Git LFS on Windows to identify files needed to be LFS's and protecting against committing binary files to non-LFS

LFS Guard is intended to provide two utilities for projects using Git LFS:

1. Identify files in repository that should be committed to LFS
2. Ensure on commit that no files being committed are binaries