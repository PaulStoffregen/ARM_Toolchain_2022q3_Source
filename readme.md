# ARM Embedded Toolchain 2022q3 (11.3.rel1)

This is a copy of the GNU toolchain published by ARM

https://developer.arm.com/downloads/-/arm-gnu-toolchain-downloads

It is compiled for other host platforms ARM doesn't build in their releases,
mainly 32 bit Raspberry Pi and 32 bit x86 (i686) Linux.

The Toolchain which PJRC publishes for Teensy is based on these builds,
but has many of the multilib folders not needed for any Teensy models
removed (dramatically reducing download size), and some additional
libraries and AVR toolchain added.

This repository is meant to help people (mainly PlatformIO users) who
have wanted to use the toolchain published for Teensy to compile programs
for running on non-Teensy hardware, with support for compiling on the
platforms (eg, Raspberry Pi) which are available on ARM's website.
