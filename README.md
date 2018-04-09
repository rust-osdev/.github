# About this Organization

The goal of this organization is to host and maintain all kinds of tools and libraries useful for operating system development in Rust. We're happy about everyone that wants to join us! Just drop by in our [gitter channel](https://gitter.im/rust-osdev/Lobby) to request an invite.

Note that we are not an official Rust organization.

## Projects
Currently we are hosting the following projects:

- [`x86_64`](https://github.com/rust-osdev/x86_64): Provides general abstractions for `x86_64` systems and access to architecture specific instructions and registers.
- [`bootloader`](https://github.com/rust-osdev/bootloader): An experimental, pure-Rust, legacy bootloader.
  - [`os_bootinfo`](https://github.com/rust-osdev/os_bootinfo): The boot information structure used by the `bootloader` to pass information (e.g. memory maps) to the kernel.
- [`bootimage`](https://github.com/rust-osdev/bootimage): A tool to transform a kernel ELF file into a bootable disk image.
- [`multiboot2-elf64`](https://github.com/rust-osdev/multiboot2-elf64): Allows parsing the boot information of the Multiboot2 standard for ELF64 kernels.

## Contributing
Contributions are more than welcome! If you have any suggestions, ideas, or projects you would like to host under this organization, don't hesitate to contact us!

## Members
The following people are currently members of this organization (alphabetically):

- Jiří Zárevúcky ([@le-jzr](https://github.com/le-jzr)): Contributor to [helenos](https://github.com/HelenOS/helenos).
- Lachlan Sneff ([@lachlansneff](https://github.com/lachlansneff)): Author of [nebulet os](https://github.com/nebulet/nebulet).
- Philipp Oppermann ([@phil-opp](https://github.com/phil-opp)): Author of the [“Writing an OS in Rust”](https://os.phil-opp.com/) series.
- Rob Gries ([@robert-w-gries](https://github.com/robert-w-gries)): Author of [rxinu](https://github.com/robert-w-gries/rxinu), a Rust implementation of the Xinu educational operating system.
