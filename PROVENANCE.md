# SPDX-License-Identifier: MPL-2.0
# Provenance

## Origin

This project was created by hyperpolymath as part of the formatrix document processing ecosystem.

## Authorship

- **Primary Author**: hyperpolymath
- **AI Assistance**: Claude (Anthropic) - code generation and documentation

## Dependencies

- **formatrix-core**: Rust library for document format conversion (hyperpolymath/formatrix-docs)
- **Zig**: Build system and runtime (ziglang.org)

## Supply Chain

This library provides Zig FFI bindings to the formatrix-core Rust library.
No C headers or C code are used - pure Zig extern declarations linking to Rust C-ABI exports.

## License Chain

- This project: MPL-2.0 + Palimpsest
- formatrix-core: MPL-2.0 + Palimpsest
- Zig stdlib: MIT
