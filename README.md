# CRYSTALS-Dilithium

## Details

### `KAT`, `rtl_src`, `rtl_tb`
This repository contains a high performance FPGA implementation of the Dilithium PQC signature algorithm written in Verilog. It contains a top module, "combined_top" which supports the operations of key generation, sign, and verify for security levels 2, 3, and 5. The three associated test benches show how to operate the module for each of these operation modes.

The design was verified in simulation using the standard 100 KATs generated by the reference implementation.

### `dilithium-256`

This folder contains the high level code that emulates the NTT design. The implementation of NTT-2x2 are in both software, and hardware style.
