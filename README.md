# iperf3 implementation for LionsOS
iperf3 client and server for LionsOS

## Prerequisites

Microkit SDK 2.20, sDDF, pip install sdfgen==0.33.0 and LLVM toolchain

## Build

make MICROKIT_BOARD=<board> MICROKIT_SDK=/path/to/microkit-sdk-2.2.0
Plus: MICROKIT_CONFIG=benchmark is required for any CPU/PMU numbers . And SMP_CONFIG=core_config/single_core.json, with two/four core unavailable.
