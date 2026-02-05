# Black Hat C++ [![Stars](https://img.shields.io/github/stars/zet235/black-hat-cpp?style=social)](https://github.com/zet235/black-hat-cpp/stargazers)

* [Black Hat C++](#black-hat-c)
* [The Things About C++](#the-things-about-c)
   * [Design Patterns](#design-patterns)
   * [Bit Flags](#bit-flags)
   * [JSON](#json)
   * [Network](#network)
   * [GUI](#gui)
* [Security](#security)
   * [Detector](#detector)
   * [Memory Hacking](#memory-hacking)
   * [Loader](#loader)
   * [Anti](#anti)
   * [Windwos API](#windwos-api)
   * [Hook](#hook)
   * [Binary Analysis](#binary-analysis)
   * [Fuzzing](#fuzzing)
   * [Exploit](#exploit)
   * [Executable Formats](#executable-formats)
   * [Backdoor](#backdoor)

# The Things About C++

- [C++ Tips of the Week](https://abseil.io/tips/)
- [C++那些事](https://github.com/Light-City/CPlusPlusThings) [![Stars](https://img.shields.io/github/stars/Light-City/CPlusPlusThings?style=social)](https://github.com/Light-City/CPlusPlusThings/stargazers)
- [Modern C++ Tutorial](https://github.com/changkun/modern-cpp-tutorial) [![Stars](https://img.shields.io/github/stars/changkun/modern-cpp-tutorial?style=social)](https://github.com/changkun/modern-cpp-tutorial/stargazers) - C++11/14/17/20 On the Fly
- [Awesome C++](https://github.com/fffaraz/awesome-cpp) [![Stars](https://img.shields.io/github/stars/fffaraz/awesome-cpp?style=social)](https://github.com/fffaraz/awesome-cpp/stargazers)
- [Windows API code snippets](https://stmxcsr.com/micro/winapi-snippets.html)
- [Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html)
- [Google 開源專案 C++ 風格指南](https://tw-google-styleguide.readthedocs.io/en/latest/google-cpp-styleguide/contents.html)
- [360 安全规则集合](https://github.com/Qihoo360/safe-rules) [![Stars](https://img.shields.io/github/stars/Qihoo360/safe-rules?style=social)](https://github.com/Qihoo360/safe-rules/stargazers)

## Design Patterns
- [JakubVojvoda/design-patterns-cpp](https://github.com/JakubVojvoda/design-patterns-cpp) [![Stars](https://img.shields.io/github/stars/JakubVojvoda/design-patterns-cpp?style=social)](https://github.com/JakubVojvoda/design-patterns-cpp/stargazers)
- [Junzhuodu/design-patterns](https://github.com/Junzhuodu/design-patterns) [![Stars](https://img.shields.io/github/stars/Junzhuodu/design-patterns?style=social)](https://github.com/Junzhuodu/design-patterns/stargazers)

## Bit Flags
- [craft::cpp](https://m-peko.github.io/craft-cpp/posts/different-ways-to-define-binary-flags/)
- [m-peko/bitflags](https://github.com/m-peko/bitflags) [![Stars](https://img.shields.io/github/stars/m-peko/bitflags?style=social)](https://github.com/m-peko/bitflags/stargazers)
- [Bitmask Operators](https://www.justsoftwaresolutions.co.uk/files/bitmask_operators.hpp)
- [enum-flags](https://github.com/grisumbras/enum-flags) [![Stars](https://img.shields.io/github/stars/grisumbras/enum-flags?style=social)](https://github.com/grisumbras/enum-flags/stargazers) - Bit flags for C++11 scoped enums
- [bitmask](https://github.com/oliora/bitmask) [![Stars](https://img.shields.io/github/stars/oliora/bitmask?style=social)](https://github.com/oliora/bitmask/stargazers) - A generic implementation of the BitmaskType C++ concept

## JSON
- [nlohmann/json](https://github.com/nlohmann/json) [![Stars](https://img.shields.io/github/stars/nlohmann/json?style=social)](https://github.com/nlohmann/json/stargazers) - JSON for Modern C++
- [simdjson/simdjson](https://github.com/simdjson/simdjson) [![Stars](https://img.shields.io/github/stars/simdjson/simdjson?style=social)](https://github.com/simdjson/simdjson/stargazers) - Parsing gigabytes of JSON per second

## Network
- [cpp-httplib](https://github.com/yhirose/cpp-httplib) [![Stars](https://img.shields.io/github/stars/yhirose/cpp-httplib?style=social)](https://github.com/yhirose/cpp-httplib/stargazers) - A C++ header-only HTTP/HTTPS server and client library
- [cpr](https://github.com/libcpr/cpr) [![Stars](https://img.shields.io/github/stars/libcpr/cpr?style=social)](https://github.com/libcpr/cpr/stargazers) - Curl for People, a spiritual port of Python Requests.
- [oatpp](https://github.com/oatpp/oatpp) [![Stars](https://img.shields.io/github/stars/oatpp/oatpp?style=social)](https://github.com/oatpp/oatpp/stargazers) - Light and powerful C++ web framework

## GUI
- [imgui](https://github.com/ocornut/imgui) [![Stars](https://img.shields.io/github/stars/ocornut/imgui?style=social)](https://github.com/ocornut/imgui/stargazers) - Bloat-free Graphical User interface for C++ with minimal dependencies

# Security

## Detector
- [memhunter](https://github.com/marcosd4h/memhunter) [![Stars](https://img.shields.io/github/stars/marcosd4h/memhunter?style=social)](https://github.com/marcosd4h/memhunter/stargazers) - Live hunting of code injection techniques
- [pe-sieve](https://github.com/hasherezade/pe-sieve) [![Stars](https://img.shields.io/github/stars/hasherezade/pe-sieve?style=social)](https://github.com/hasherezade/pe-sieve/stargazers) - Recognizes and dumps a variety of potentially malicious implants
- [hollows hunter](https://github.com/hasherezade/hollows_hunter) [![Stars](https://img.shields.io/github/stars/hasherezade/hollows_hunter?style=social)](https://github.com/hasherezade/hollows_hunter/stargazers) - Scans all running processes. Recognizes and dumps a variety of potentially malicious implants (replaced/implanted PEs, shellcodes, hooks, in-memory patches).
- [BLUESPAWN](https://github.com/ION28/BLUESPAWN) [![Stars](https://img.shields.io/github/stars/ION28/BLUESPAWN?style=social)](https://github.com/ION28/BLUESPAWN/stargazers) - An Active Defense and EDR software to empower Blue Teams
- [CobaltStrikeDetected](https://github.com/huoji120/CobaltStrikeDetected) [![Stars](https://img.shields.io/github/stars/huoji120/CobaltStrikeDetected?style=social)](https://github.com/huoji120/CobaltStrikeDetected/stargazers) - 40行代码检测到大部分CobaltStrike的shellcode

## Memory Hacking
- [Blackbone](https://github.com/DarthTon/Blackbone) [![Stars](https://img.shields.io/github/stars/DarthTon/Blackbone?style=social)](https://github.com/DarthTon/Blackbone/stargazers) - Windows memory hacking library
- [herpaderping](https://github.com/jxy-s/herpaderping) [![Stars](https://img.shields.io/github/stars/jxy-s/herpaderping?style=social)](https://github.com/jxy-s/herpaderping/stargazers) - bypasses security products by obscuring the intentions of a process
- [pinjectra](https://github.com/SafeBreach-Labs/pinjectra) [![Stars](https://img.shields.io/github/stars/SafeBreach-Labs/pinjectra?style=social)](https://github.com/SafeBreach-Labs/pinjectra/stargazers) - Pinjectra is a C/C++ OOP-like library that implements Process Injection techniques
- [PowerLoaderEx](https://github.com/BreakingMalware/PowerLoaderEx) [![Stars](https://img.shields.io/github/stars/BreakingMalware/PowerLoaderEx?style=social)](https://github.com/BreakingMalware/PowerLoaderEx/stargazers) - PowerLoaderEx - Advanced Code Injection Technique for x32 / x64
- [FunctionStomping](https://github.com/Idov31/FunctionStomping) [![Stars](https://img.shields.io/github/stars/Idov31/FunctionStomping?style=social)](https://github.com/Idov31/FunctionStomping/stargazers) - A new shellcode injection technique. Given as C++ header, standalone Rust program or library.

## Loader

- [MemLoader](https://github.com/NtDallas/MemLoader) [![Stars](https://img.shields.io/github/stars/NtDallas/MemLoader?style=social)](https://github.com/NtDallas/MemLoader/stargazers) - Run native PE or .NET executables entirely in-memory.
- [donut](https://github.com/TheWover/donut) [![Stars](https://img.shields.io/github/stars/TheWover/donut?style=social)](https://github.com/TheWover/donut/stargazers) - Generates x86, x64, or AMD64+x86 position-independent shellcode that loads .NET Assemblies, PE files, VBScript, JScript and runs them from memory with parameters. 

## Anti
- [al-khaser](https://github.com/LordNoteworthy/al-khaser) [![Stars](https://img.shields.io/github/stars/LordNoteworthy/al-khaser?style=social)](https://github.com/LordNoteworthy/al-khaser/stargazers) - Public malware techniques used in the wild: Virtual Machine, Emulation, Debuggers, Sandbox detection.
- [gargoyle](https://github.com/JLospinoso/gargoyle) [![Stars](https://img.shields.io/github/stars/JLospinoso/gargoyle?style=social)](https://github.com/JLospinoso/gargoyle/stargazers) - A memory scanning evasion technique
- [anti-sandbox](https://github.com/ZanderChang/anti-sandbox) [![Stars](https://img.shields.io/github/stars/ZanderChang/anti-sandbox?style=social)](https://github.com/ZanderChang/anti-sandbox/stargazers) - Windows对抗沙箱和虚拟机的方法总结
- [makin](https://github.com/secrary/makin) [![Stars](https://img.shields.io/github/stars/secrary/makin?style=social)](https://github.com/secrary/makin/stargazers) - reveal anti-debugging and anti-VM tricks
- [obfusheader.h](https://github.com/ac3ss0r/obfusheader.h) [![Stars](https://img.shields.io/github/stars/ac3ss0r/obfusheader.h?style=social)](https://github.com/ac3ss0r/obfusheader.h/stargazers) - portable header file for C++14 compile-time obfuscation
- [obfus.h](https://github.com/DosX-dev/obfus.h) [![Stars](https://img.shields.io/github/stars/DosX-dev/obfus.h?style=social)](https://github.com/DosX-dev/obfus.h/stargazers) - Macro-header for compile-time C obfuscation (tcc, win x86/x64)
- [Obfusk8](https://github.com/x86byte/Obfusk8) [![Stars](https://img.shields.io/github/stars/x86byte/Obfusk8?style=social)](https://github.com/x86byte/Obfusk8/stargazers) - lightweight Obfuscation library based on C++17 / Header Only for windows binaries

## Windwos API
- [wow64pp](https://github.com/JustasMasiulis/wow64pp) [![Stars](https://img.shields.io/github/stars/JustasMasiulis/wow64pp?style=social)](https://github.com/JustasMasiulis/wow64pp/stargazers) - A modern c++ implementation of windows heavens gate
- [SysWhispers](https://github.com/jthuraisamy/SysWhispers) [![Stars](https://img.shields.io/github/stars/jthuraisamy/SysWhispers?style=social)](https://github.com/jthuraisamy/SysWhispers/stargazers) - AV/EDR evasion via direct system calls.
- [SysWhispers2](https://github.com/jthuraisamy/SysWhispers2) [![Stars](https://img.shields.io/github/stars/jthuraisamy/SysWhispers2?style=social)](https://github.com/jthuraisamy/SysWhispers2/stargazers) - AV/EDR evasion via direct system calls.
- [HWSyscalls](https://github.com/Dec0ne/HWSyscalls) [![Stars](https://img.shields.io/github/stars/Dec0ne/HWSyscalls?style=social)](https://github.com/Dec0ne/HWSyscalls/stargazers) - execute indirect syscalls using HWBP, HalosGate and a synthetic trampoline on kernel32 with HWBP
- [syscalls-cpp](https://github.com/sapdragon/syscalls-cpp) [![Stars](https://img.shields.io/github/stars/sapdragon/syscalls-cpp?style=social)](https://github.com/sapdragon/syscalls-cpp/stargazers) - A modern C++20 header-only library for advanced direct system call invocation.
- [CallObfuscator](https://github.com/d35ha/CallObfuscator) [![Stars](https://img.shields.io/github/stars/d35ha/CallObfuscator?style=social)](https://github.com/d35ha/CallObfuscator/stargazers) - Obfuscate specific windows apis with different apis
- [UnhookMe](https://github.com/mgeeky/UnhookMe) [![Stars](https://img.shields.io/github/stars/mgeeky/UnhookMe?style=social)](https://github.com/mgeeky/UnhookMe/stargazers) - UnhookMe is an universal Windows API resolver & unhooker addressing problem of invoking unmonitored system calls from within of your Red Teams malware
- [lazy_importer](https://github.com/JustasMasiulis/lazy_importer) [![Stars](https://img.shields.io/github/stars/JustasMasiulis/lazy_importer?style=social)](https://github.com/JustasMasiulis/lazy_importer/stargazers) - header only library to make the life of a reverse engineer much harder.
- [inline_syscall](https://github.com/JustasMasiulis/inline_syscall) [![Stars](https://img.shields.io/github/stars/JustasMasiulis/inline_syscall?style=social)](https://github.com/JustasMasiulis/inline_syscall/stargazers) - Inline syscalls made easy for windows on clang
- [RefleXXion](https://github.com/hlldz/RefleXXion) [![Stars](https://img.shields.io/github/stars/hlldz/RefleXXion?style=social)](https://github.com/hlldz/RefleXXion/stargazers) - bypassing user-mode hooks utilised by AV/EPP/EDR etc.

## Hook
- [InfinityHook](https://github.com/everdox/InfinityHook) [![Stars](https://img.shields.io/github/stars/everdox/InfinityHook?style=social)](https://github.com/everdox/InfinityHook/stargazers) - Hook system calls, context switches, page faults and more.
- [minhook](https://github.com/TsudaKageyu/minhook) [![Stars](https://img.shields.io/github/stars/TsudaKageyu/minhook?style=social)](https://github.com/TsudaKageyu/minhook/stargazers) - The Minimalistic x86/x64 API Hooking Library for Windows

## Binary Analysis
- [Triton](https://github.com/JonathanSalwan/Triton) [![Stars](https://img.shields.io/github/stars/JonathanSalwan/Triton?style=social)](https://github.com/JonathanSalwan/Triton/stargazers) - It provides internal components like a Dynamic Symbolic Execution (DSE) engine
- [zasm](https://github.com/ZehMatt/zasm) [![Stars](https://img.shields.io/github/stars/ZehMatt/zasm?style=social)](https://github.com/ZehMatt/zasm/stargazers) - x86-64 Assembler based on Zydis
- [retdec](https://github.com/avast/retdec) [![Stars](https://img.shields.io/github/stars/avast/retdec?style=social)](https://github.com/avast/retdec/stargazers) - RetDec is a retargetable machine-code decompiler based on LLVM.
- [PinTools](https://github.com/JonathanSalwan/PinTools) [![Stars](https://img.shields.io/github/stars/JonathanSalwan/PinTools?style=social)](https://github.com/JonathanSalwan/PinTools/stargazers) - Pintool example and PoC for dynamic binary analysis

## Fuzzing
- [libfuzzer](https://github.com/Dor1s/libfuzzer-workshop) [![Stars](https://img.shields.io/github/stars/Dor1s/libfuzzer-workshop?style=social)](https://github.com/Dor1s/libfuzzer-workshop/stargazers) - Repository for materials of "Modern fuzzing of C/C++ Projects" workshop.

## Exploit
- [pwn++](https://github.com/hugsy/pwn--) [![Stars](https://img.shields.io/github/stars/hugsy/pwn--?style=social)](https://github.com/hugsy/pwn--/stargazers) - pwn++ is a Windows & Linux library oriented for exploit dev but mostly used to play with modern C++ features

## Executable Formats
- [LIEF](https://github.com/lief-project/LIEF) [![Stars](https://img.shields.io/github/stars/lief-project/LIEF?style=social)](https://github.com/lief-project/LIEF/stargazers) - Library to Instrument Executable Formats

## Backdoor
- [IIS-Raid](https://github.com/0x09AL/IIS-Raid) [![Stars](https://img.shields.io/github/stars/0x09AL/IIS-Raid?style=social)](https://github.com/0x09AL/IIS-Raid/stargazers) - A native backdoor module for Microsoft IIS
