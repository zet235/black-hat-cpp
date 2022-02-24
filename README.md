# Black Hat C++

- [The Things About C++](#the-things-about-c)
  - [Design Patterns](#design-patterns)
  - [Bit Flags](#bit-flags)
  - [JSON](#json)
  - [Network](#network)
  - [GUI](#gui)
- [Security](#security)
  - [Detector](#detector)
  - [Memory Hacking](#memory-hacking)
  - [Anti](#anti)
  - [Windwos API](#windwos-api)
  - [Hook](#hook)
  - [Binary Analysis](#binary-analysis)
  - [fuzzing](#fuzzing)
  - [Executable Formats](#executable-formats)
  - [Backdoor](#backdoor)

# The Things About C++

- [C++ Tips of the Week](https://abseil.io/tips/)
- [C++那些事](https://github.com/Light-City/CPlusPlusThings)
- [Modern C++ Tutorial](https://github.com/changkun/modern-cpp-tutorial) - C++11/14/17/20 On the Fly
- [Awesome C++](https://github.com/fffaraz/awesome-cpp)
- [Windows API code snippets](https://stmxcsr.com/micro/winapi-snippets.html)
- [Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html)
- [Google 開源專案 C++ 風格指南](https://tw-google-styleguide.readthedocs.io/en/latest/google-cpp-styleguide/contents.html)

## Design Patterns
- [JakubVojvoda/design-patterns-cpp](https://github.com/JakubVojvoda/design-patterns-cpp)
- [Junzhuodu/design-patterns](https://github.com/Junzhuodu/design-patterns)

## Bit Flags
- [craft::cpp](https://m-peko.github.io/craft-cpp/posts/different-ways-to-define-binary-flags/)
- [m-peko/bitflags](https://github.com/m-peko/bitflags)
- [Bitmask Operators](https://www.justsoftwaresolutions.co.uk/files/bitmask_operators.hpp)
- [enum-flags](https://github.com/grisumbras/enum-flags) - Bit flags for C++11 scoped enums
- [bitmask](https://github.com/oliora/bitmask) - A generic implementation of the BitmaskType C++ concept

## JSON
- [nlohmann/json](https://github.com/nlohmann/json) - JSON for Modern C++
- [simdjson/simdjson](https://github.com/simdjson/simdjson) - Parsing gigabytes of JSON per second

## Network
- [cpp-httplib](https://github.com/yhirose/cpp-httplib) - A C++ header-only HTTP/HTTPS server and client library
- [cpr](https://github.com/libcpr/cpr) - Curl for People, a spiritual port of Python Requests.
- [oatpp](https://github.com/oatpp/oatpp) - Light and powerful C++ web framework

## GUI
- [imgui](https://github.com/ocornut/imgui) - Bloat-free Graphical User interface for C++ with minimal dependencies

# Security

## Detector
- [memhunter](https://github.com/marcosd4h/memhunter) - Live hunting of code injection techniques
- [pe-sieve](https://github.com/hasherezade/pe-sieve) - Recognizes and dumps a variety of potentially malicious implants
- [hollows hunter](https://github.com/hasherezade/hollows_hunter) - Scans all running processes. Recognizes and dumps a variety of potentially malicious implants (replaced/implanted PEs, shellcodes, hooks, in-memory patches).
- [BLUESPAWN](https://github.com/ION28/BLUESPAWN) - An Active Defense and EDR software to empower Blue Teams
- [CobaltStrikeDetected](https://github.com/huoji120/CobaltStrikeDetected) - 40行代码检测到大部分CobaltStrike的shellcode

## Memory Hacking
- [Blackbone](https://github.com/DarthTon/Blackbone) - Windows memory hacking library
- [herpaderping](https://github.com/jxy-s/herpaderping) - bypasses security products by obscuring the intentions of a process
- [pinjectra](https://github.com/SafeBreach-Labs/pinjectra) - Pinjectra is a C/C++ OOP-like library that implements Process Injection techniques
- [PowerLoaderEx](https://github.com/BreakingMalware/PowerLoaderEx) - PowerLoaderEx - Advanced Code Injection Technique for x32 / x64
- [FunctionStomping](https://github.com/Idov31/FunctionStomping) - A new shellcode injection technique. Given as C++ header, standalone Rust program or library.

## Anti
- [al-khaser](https://github.com/LordNoteworthy/al-khaser) - Public malware techniques used in the wild: Virtual Machine, Emulation, Debuggers, Sandbox detection.
- [gargoyle](https://github.com/JLospinoso/gargoyle) - A memory scanning evasion technique
- [anti-sandbox](https://github.com/ZanderChang/anti-sandbox) - Windows对抗沙箱和虚拟机的方法总结
- [makin](https://github.com/secrary/makin) - reveal anti-debugging and anti-VM tricks

## Windwos API
- [wow64pp](https://github.com/JustasMasiulis/wow64pp) - A modern c++ implementation of windows heavens gate
- [SysWhispers](https://github.com/jthuraisamy/SysWhispers) - AV/EDR evasion via direct system calls.
- [SysWhispers2](https://github.com/jthuraisamy/SysWhispers2) - AV/EDR evasion via direct system calls.
- [CallObfuscator](https://github.com/d35ha/CallObfuscator) - Obfuscate specific windows apis with different apis
- [UnhookMe](https://github.com/mgeeky/UnhookMe) - UnhookMe is an universal Windows API resolver & unhooker addressing problem of invoking unmonitored system calls from within of your Red Teams malware
- [lazy_importer](https://github.com/JustasMasiulis/lazy_importer) - header only library to make the life of a reverse engineer much harder.
- [inline_syscall](https://github.com/JustasMasiulis/inline_syscall) - Inline syscalls made easy for windows on clang
- [RefleXXion](https://github.com/hlldz/RefleXXion) - bypassing user-mode hooks utilised by AV/EPP/EDR etc.

## Hook
- [InfinityHook](https://github.com/everdox/InfinityHook) - Hook system calls, context switches, page faults and more.
- [minhook](https://github.com/TsudaKageyu/minhook) - The Minimalistic x86/x64 API Hooking Library for Windows

## Binary Analysis
- [Triton](https://github.com/JonathanSalwan/Triton) - It provides internal components like a Dynamic Symbolic Execution (DSE) engine
- [zasm](https://github.com/ZehMatt/zasm) - x86-64 Assembler based on Zydis
- [retdec](https://github.com/avast/retdec) - RetDec is a retargetable machine-code decompiler based on LLVM.
- [PinTools](https://github.com/JonathanSalwan/PinTools) - Pintool example and PoC for dynamic binary analysis

## fuzzing
- [libfuzzer](https://github.com/Dor1s/libfuzzer-workshop) - Repository for materials of "Modern fuzzing of C/C++ Projects" workshop.

## Executable Formats
- [LIEF](https://github.com/lief-project/LIEF) - Library to Instrument Executable Formats

## Backdoor
- [IIS-Raid](https://github.com/0x09AL/IIS-Raid) - A native backdoor module for Microsoft IIS
