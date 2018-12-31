# XVolkolak for Windows

###     Usage of XVolkolak

Scan – scan a file for Packer/Protector information.

Unpack – unpack a file.

If the auto unpacking failed, try Advanced mode.
Press Advanced.

Select Generic method.

Press Analyze

Change if necessary OEP and Import

Press Unpack

###   XVolkolak Description

XVolkolak is an unpacker emulator

Unlike programs of this type, it does not use DebugAPI and other features of the operating system. Everything is emulated. You can safely unpack malware for further investigation without the risk of damaging the system.
All machine instructions are not executed on a real processor, so unpacking occurs regardless of the processor type and the operating system.
It is possible to unpack 64 bit files on 32 operating systems.
This build emulates the processors intel x86 and AMD64.
It supports unpacking 32 and 64 bit Windows executable files. If there is community interest, it will be possible to unpack other executable files (ELF, MSDOS, Mach-O) and other processors.

Due to its capabilities, with the correct manual setting, the program engine can be used to unpack almost any packer / protector.
However, this version of the program works in a fully automatic mode and can only unpack simple non-commercial unpackers such as:

UPX
ASPack
NsPack
Mpress
MEW
(Win) Upack
FSG
and some others.

The version of the program with the possibility of unpacking commercial protectors (such as VMProtect, ASProtect and others) will not appear in the public domain for obvious reasons.


###     Console version of XVolkolak

There is also console version of program (xvlkc.exe). It’s in the folder "base"
xvlkc.exe –S <filename> scan a file
xvlkc.exe <filename> unpack a file
