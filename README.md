These are the source files for builing the MMDVMHost, the program that interfaces to the MMDVM or DVMega on the one side, and a suitable network on the other. On the D-Star side the MMDVMHost interfaces with the ircDDB Gateway, on DMR, only the BrandMeister network currently.

It supports D-Star, DMR, and System Fusion.

It builds on 32-bit and 64-bit Linux as well as on Windows using VS2015 on x86 and x64. It can optionally control various Displays. Currently these are:

- HD44780 (sizes 2x16, 2x40, 4x16, 4x20)
- Nextion TFTs (sizes 2,4" and 3,5")
- TFT displays sold by Hobbytronics in UK

The HD44780 displays are integrated with wiringPi for Raspberry Pi based platforms. The other displays can be directly connected to the UART on Raspberry Pis or with FT-232RL modules to any USB port.

This software is licenced under the GPL v2 and is intended for amateur and educational use only. Use of this software for commercial purposes is strictly forbidden.

It is only to be used on the main DMR+, the main BrandMeister, and Phoenix (UK) networks. If you wish to use it on any other network, you must get written permission from myself, G4KLX. Each such request will be dealt with on a case-by-case basis.
