# T80 a Z80 Compatible Microprocessor Gateware IP Core

Configurable CPU core that supports Z80, 8080 and Gameboy instruction sets. Z80 and 8080 compatibility have been proven by numerous implementations of vintage computers, consoles and arcade systems.

A Z80 SoC debug system with ROM, RAM and two 16450 UARTs is included in the distribution.

## Features

- Technology independent
- 10k gates and up to 100MHz in 0.18 CMOS
- Supports all undocumented Z80 instructions
- Supports all Z80 interrupt modes
- Correct R register behavior
- Correct Z80 instruction timing
- Almost 100% correct behavior of the undocumented Z80 flags
- Both a synchronous (for implementation) and an asynchronous (for board level simulations) Z80 top level
- Only a synchronous 8080 top level

## Status

- Z80 compatibility and functionality thoroughly verified in FPGA
- The Gameboy mode is experimental
- No Gameboy top level

## Changelog

All notable changes are documented in the [CHANGELOG](CHANGELOG.md).

## Credits and acknowledgment

- MikeJ
- ZXGATE project members
- Sean Riddle
- TobiFlex
- Alexey Melnikov
- Bruno Duarte Gouveia

## Legal Notices

[T80](https://opencores.org/projects/t80) - Copyright (c) 2001-2002 Daniel Wallner. All rights reserved.

This work is licensed under multiple licenses.

- All original source code is licensed under [BSD 3-Clause "New" or "Revised" License](https://spdx.org/licenses/BSD-3-Clause.html) unless implicit indicated.
- All documentation is licensed under [Creative Commons Attribution Share Alike 4.0 International](https://spdx.org/licenses/CC-BY-SA-4.0.html) Public License.
- Some configuration and data files are licensed under [Creative Commons Zero v1.0 Universal](https://spdx.org/licenses/CC0-1.0.html).

Open Gateware and any contributors reserve all others rights, whether under their respective copyrights, patents, or trademarks, whether by implication, estoppel or otherwise.

Individual files may contain the following SPDX license tags as a shorthand for the above copyright and warranty notices:

```text
SPDX-License-Identifier: BSD-3-Clause
SPDX-License-Identifier: CC-BY-SA-4.0
SPDX-License-Identifier: CC0-1.0
```

This eases machine processing of licensing information based on the SPDX License Identifiers that are available at [spdx.org/licenses](https://spdx.org/licenses/).

The Open Gateware authors and contributors or any of its maintainers are in no way associated with or endorsed by Intel®, Altera®, AMD®, Xilinx®, Lattice®, Microsoft® or any other company not implicit indicated. All other brands or product names are the property of their respective holders.
