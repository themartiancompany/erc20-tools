[comment]: <> (SPDX-License-Identifier: AGPL-3.0)

[comment]: <> (------------------------------------------------------)
[comment]: <> (Copyright © 2024, 2025, 2026  Pellegrino Prevete)
[comment]: <> (All rights reserved)
[comment]: <> (------------------------------------------------------)

[comment]: <> (This program is free software: you can redistribute)
[comment]: <> (it and/or modify it under the terms of the GNU Affero)
[comment]: <> (General Public License as published by the Free)
[comment]: <> (Software Foundation, either version 3 of the License.)

[comment]: <> (This program is distributed in the hope that it will be)
[comment]: <> (useful, but WITHOUT ANY WARRANTY; without even the)
[comment]: <> (implied warranty of MERCHANTABILITY or FITNESS FOR)
[comment]: <> (A PARTICULAR PURPOSE. See the)
[comment]: <> (See the GNU Affero General Public License for)
[comment]: <> (more details.)

[comment]: <> (You should have received a copy of the GNU Affero)
[comment]: <> (General Public License along with this program.)
[comment]: <> (If not, see <https://www.gnu.org/licenses/>.)

# Ethereum \*RC-20 tokens Tools (`erc20-tools`)

JavaScript programs and libraries to enable seamless development
of native computer applications designed to interact
with Ethereum \*RC-20 tokens on Ethereum Virtual Machine-compatible
networks. 

Since \*RC-20 tokens are smart contracts to interact with those
is necessary to perform smart contracts calls, so
[EVM Contracts Tools](
  https://github.com/themartiancompany/evm-contracts-tools)
is a dependency.

[EVM Wallet](
  https://github.com/themartiancompany/evm-wallet)
use it as an optional dependency in order to avoid
a depedency cycle; as a consequence *one needs to explicitly
install \*RC-20 support for EVM Wallet to handle \*RC-20
tokens*.

The `erc20-token-send` program uses the 
[Ethers](
  https://github.com/ethers-io/ethers.js)
JavaScript library under the hood to
communicate with Ethereum Virtual Machine-compatible
blockchain networks.

## Installation

The tools in this source repo
can be installed from source using GNU Make.

```bash
make \
  install
```

The collection has been officially published
on the the uncensorable
[Ur](
  https://github.com/themartiancompany/ur)
user repository and application store as
`erc20-tools`.
The source code is published on the
[Ethereum Virtual Machine File System](
  https://github.com/themartiancompany/evmfs)
so it can't possibly be taken down.

To install it from there just type

```bash
ur \
  erc20-tools
```

A censorable HTTP Github mirror of the recipe published there,
containing a full list of the software dependencies needed to run the
tools is hosted on
[erc20-tools-ur](
  https://github.com/themartiancompany/erc20-tools-ur).

Be aware the mirror could go offline any time as Github and more
in general all HTTP resources are inherently unstable and censorable.

## License

This program is released by Pellegrino Prevete under the terms
of the GNU Affero General Public License version 3.
