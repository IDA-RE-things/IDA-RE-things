Time to say about me? Ok.
### Hi there 👋

My achievements, some facts, interests, and work in progress (not commercial, just for me), **_related to software_**. which I have divided to categories:
<hr>

Distant past. From what all was started. Post-school years (pre 2000, pre x86-PC) Just for history:
- [No Computer at all]: I have read books and magazines about programming, later have bought programmed micro-calculator `MK52`, and modified it to speedup.
 Have reversed (published in magazines) programs for it; from hex-like codes. 
 Also was intrested in microprocessor 8080 (how it can work, if imagine it on separate logic IC's). microprocessor which I seen only in magazines. 
 Have tried to write small asm programs just on paper, investigating algorithms and writing diagrams.
 Also found interesting mini CPM-compatible operating system for minicomputer for hobbists.
- [Still no computer]. Have repaired ZX-Spectrum Computer PCB from one of my friends. PCB was researched by by me, cutting connections between IC's and watching signals, then found and fixed bug on PCB. Thus, I became familarized with a working ZX-Spectrum computer (on z80 , which was based on 8080). (~1994).
- [Ok, farther. some years later bought my own ZX-Spectrum compatible computer. But there are no convenient tools around]: Starting to make assembler programs from the books. The compact Assembler/Disassembler package, called `HiSoft DevPack`, which I have found on cassete, was reversed by me and extended, to do compact store of large disassembled listings in 48k only Spectrum memory; Combined with more friendly editor from Pascal, and with screen driver from another package, to show 64 symbols per line instead of 32. Also all in z80 asm.
- ** Initial large work on disassembling and renaming functions, determining the purpose of functions and their parameters, tracking registers and so on, was done by me just in school notebooks and with colored pens. No such thing that time as IDA now on PC :)
- [Then]: Revers'ed and improved `Hisoft Pascal` compiler for ZX-Spectrum (1st course of university times). Done on Spectrum itself. Using above disassembler/debugger/editor tools I reworked before. The resulting "Pascal compiler system" on the tape, allow me have then making large pascal program to do computation of schemes for radioelectronic, ported by me from Basic language from radio-magazine, and improved.  (~1997 y)
- The above mini-CPM-compatible operating system for 8080 was reversed by me from binary codes, which I entered from hex-codes by hands into computer (~4 kb).
- ** All above work was done only with cassetes as information store. With the custom tape recorder, which I have modified to speedup and stability (reliability) of loading programs from cassete tapes.
- reversing of fine-coded Autosimulator game (`HardDrivin`) for ZX Spectrum. (~1999 y)
<hr>

Later and now:
### Compilers/Decompilers:
- Reverse-engineering of Optimizing `MSX-C/SOLID-C (z80) Compiler`'s Backend (Optimizer and Codegenerator) -- (writen in z80. Task was done using IDA 3.7 disassembler, and printer to read wide C src listings, which I wrote from reversed code. Task started in 1998. spend 1.5 years on IBM PC 486) it took long-time, binary was recreated back to C-source code). Also to debug it, ZXSpectrum emulator, patched by me to run MSX/CPM-code was used, And reversed/modified z80 CPM emulator. Then I'm fixed bugs, extending features., improved register allocation. And ported it to x86 as crosscompiler. Fixed z80-based Solid-C was posted by me to ZX-Spectrum related FidoNet group, for people and community (~2002 y).
- Reversing/researching of old `Borland C++ 3.1` for Dos. Im was using it under Dos box on Win'95. It was my 1st IDE to work with C programs on my `486-DX-100` PC. Also I have porting of above Solid-C z80 to x86 as cross-compiler with this Borland IDE, And writing reversed compiler code also with this IDE.
- ** To debug above SOLID-C memory dumps, I'm using Borland IDE for x86, but compiling it with "small" memory model, and loading existing 64k memory dump as data segment from z80 emulator to it at runtime;
- research and reversing (if no src) of others existing z80/8080/i386 compilers for DOS/Win/CPM/Spectrum.
- `VBCC` portable optimizing compiler rework/refactoring/extending (spent many time) of i386, z80, etc.
- reversing/researching of `IAR embedded C compiler for z80` internals.
- reversing/researching of `Intel C/C++ compiler` internals.
- reversing/researching of `Borland C/C++ compiler` internals.
- reversing of `Watcom C/C++ compiler`. And later, when it stay open-sourced Open-watcom, => extending Watcom compiler/tools to support CV debug info for ex.
- large R/E of `MS VC Compiler/tools`, created compatibility with Borland compilers, adding work with register Custom-calling conventions, and other.
- Partially reversed internal `MS BBTools`, reversed intermediate data formats
- MFC (MS) & VCL (Borland), -related decompilers
- Reversing/researching of `MS VisualBasic 6.0 compiler` (which was able to generate native code).
- Converitng interesting for me projects (from third persons) from Delphi to C++.
- Improving/researching/reversing of other existing decompiler's (before HexRays was born)
- Extending `IDA/Hexrays` (including long-time reversing), writing additional tools, Created plugins. (some done, some in progress)

### Windows internals:
- I'm prefer Windows XP, because of its leaked src code. And dont moving totally to Windows7. (While using in parallel). If I found some bugs, I'm rely only to myself. As with owned legacy (but nice) car from 2000x.
- reworked and recompiled leaked Windows NT code, +created and reworked tools for it.
- I'm have created my own custom Win7+ API emulation libraryes to run some new programs on WinXP.
- time-to-time working with/reversing of Win32-related system DLL's. 

### Other OS's:
- Interested in `KolibriOS`, written mostly in asm code. Interested in translate most parts to C source. To improve, extending, support and debugging of it. Have created IDA plugin to improve this. And its work in progress.
- some work for KolibriOS emulator for Windows, translating it to C and rework. (originally written in Delphi by other people). 

### Graphics Cards:
- research of internals of proprietary `Radeon HD` and `NVidia` drivers (no src of course)

### Speech generation:
- research and reversing of text-to-speech generation software

### DirectX:
- Research/Reversing of `MS DirectX` code, `PIX` profiler, etc
- Interested with DirectX-11 emulation for WinXP. (under research)

### Game Consoles:
- XBox (original) : was interested in reversing and emulation of it. Bought 3 instances of it for this experiments. Researched leaked Xbox sources. And state of art in existing emulators.
- Reversing of PS3-based games (some interesting autosimulators).

### RadioElectronic/CAD:
- research/reversing/fixing/rework. of various programs/packages/products
- retrieving schemes from PCB (reversing), and other.
- Repairing.
- I'm radio-hobbyst in earlier years. (and stay now)

### Computer hardware:
- Motherboard repair: Bought POST-cards, have revers'ed firmware for one of it. Researched, have found and fixed the cause of computer off on motherboard.

### Emulation:
- interested in `Virtual PC` and other emulation/virtualization software. Revers'ed some parts.
- Z80-based computers emulation (`blueMSX`, `UnrealSpeccy`, etc),
- `XBox` emulation,
- reversing/improving of software-emulated debuggers for microcontrollers

### MIDI/VSTi/DAW/Music:
- Love `SpaceSynth`-style music and try to research and make it.
- fixed software, working with new MIDI-keyboards to support legacy keyboard.
- `ASIO` for WinXP.
- Research/Reversing of `Roland GS`, and `Yamaha XG` software synthesizers. (`SYXG50` and `YMF744/724`). bought ~15 pieces for collection.
- research/reversing/fixing/ of different DAW for composers.
- MIDI devices repair and reversing.

### Autosimulators/ActionGames
- Extending/Research of many Autosimulator-related games. w/o source code. (for ex `Driver SF`, `Grid Autosport`, `CrashTime` -series, and many others)
- Develop/revesing of own autosim from partial source code. (`Racer`-based)
- Reversing of `CryEngine3` -based games, and `CineBox` workshop/editors, to extend functionality
- Interesting in learing of `GTA3/SA` reversed game sources.
- Also interested in other reversed/leaked game code sources.

### Automotive:
- reversing/research of old BOSCH ECU's firmware code (`Motronic` different versions). (i8051/- based chips)
- (one such Motronic was repaired by me for my car in 2006, while no one wanted to repair it before on stations).
- ECU-diagnostic software research/reversing.
- other autoelectronics
 
### Microcontrollers:
- reversing of `AVR`- and `i8051`- based MCU firmwares
- improvemet of IDA plugins for it, etc.
- reversing/extending of proprietary commercial tools for it. To improve functionality.

### Internet:
- Reversing of proprietary `MS Exchange ESE/EDB` engine and database data formats, to work with email-databases (commercial work, 2004-2006).
- Reversed proprietary binary database format of `FlashGet 1.9` downloader (was abandoned by authors), fixed internal hard-to-find bugs. Created database repair utility. Drastically improved performance of large database loading on startup (**_from 5-10 min to 2 sec_**); Also added possibility to work with huge databases without crash at some time and data corruption. (And this was without source code) (2008-2024).
- R/E, fixing, extending `Proxomitron` proxy-server (no src). Also created many complicated filters for it.
- Fixed/reversed `HandyCache` proxy-server (no src).
- Reversed parts of `MS IE8` browser for XP, and created module to fix issues with performance inside `MSHTML.dll` component. The problem was inside font caching algorithms. I have fixed and improved it. And now its flying. Also CHM viewer improved/optimized.
- Have own knowlege system, based on reversengineering of abandoned `WebResearch` software.
- Reversing/Improving `MyIE`-based browser (w/MFC src)
- improving `Opera` browser (w/leaked src)
- Fixing `Chrome` browser to improve speedup

### Other:
- `Far manager` and plugins rework.
- R/E extending/bugfixing in binary code of Windows desktop Applications.

- and other (not in my memory now) ....
<hr>

### My preferences:
- I'm prefer VisualStudio 2008 for develop, when its possible.
- I'm prefer IDA 6.8 for reversing with it. (For several reasons).
- I'm prefer simple possible code, which can be compiled with many other compilers. Dont like new C++ standards. While its intended to simplicity of code writings. (The `auto` keyword, lambda's, and so on). But such code can not be compiled with old compilers. And I'm tired to rewrite it, when this occurs in projects code, wich I want to compile with VS2008 for ex.
- dont like using of STL code, without real necessity.
- dont like `cout << hex() << something;`; but like `printf("%08x", something);`. Because its more compact, flexible, and understandable. Especially for reversing.
- I like good commented code (but not over-commented). And always do such.
- do refactoring, when needed.
- dont like bloated and fat software. but I like small, lightweight, fast, and well-coded.
- and so on.
- the code, which I wrote even 25 years ago, I dont need to rewrite, because it was good writen and with a good style.
<hr>


