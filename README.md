Hardware-Implementation-of-Lightweight-Block-Ciphers
This repository contains Verilog RTL implementations of lightweight block ciphers designed for efficient hardware-based cryptography, targeting ASIC applications.

The project specifically includes:

✅ Simon 32/64
✅ Speck 32/64
✅ Simeck 32/64

Each cipher follows a modular Verilog design, consisting of:

Key Generation Module

Encryption Module

Top Module (integrating key generation and encryption)

Testbenches are provided for each design to verify functionality through simulation, ensuring correct key scheduling and encryption processes. The designs are intended for lightweight, resource-constrained environments where efficient cryptography is critical.

