<div align="center">

# ISLAB

## Immutable Memory Management Metadata for Commodity Operating System Kernels

</div>

This repository contains the source code of the ISLAB prototype published at ACM AsiaCCS 2024.
The provided patch files contain our kernel modifications that implement the two ISLAB features:

- `ISLAB-ksmap-cred.patch`: implements the SMAP-based isolation feature
- `ISLAB-pointer-segregation.patch`: implements the pointer-segregation feature
- `linux-kernel`: the source files of the unmodified (vanilla) Linux kernel v5.11
