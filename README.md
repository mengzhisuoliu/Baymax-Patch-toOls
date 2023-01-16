
# Baymax-Patch-toOls

1. Baymax Patch Tools releases a hijacked DLL for the target process to load the functional module PYG.DLL, realizing dynamic patching of the target process. it not only supports dynamically modifying instructions and data of the target module, but also simulates the OD break function, which can modify the corresponding registers, flag registers and memory data of the registers pointing to memory after breaking the target module, so as to achieve cracking it without modifying the target file.
2. It supports the following two kinds of patching functions: Search and Replace Patch, which can directly modify the instruction code or memory data in the process memory by locating the memory address through the feature code or offset address. Exception Breakpoint Patch, support the abnormal interrupt function of the simulated debugger, by setting and triggering the interrupt after modifying registers, memory and other data to achieve the purpose of modifying the program execution process and so on.
3. The tool is protected by a shell, and the antivirus may misreport the tool and the patch file! Due to the use of the shell SDK, all components of the tool (including the generated patches) do not contain networking capabilities! The generated patches will not modify any files in the system when running (except for overwriting patch files). The generated patches will not modify any files in the system when running (except for overwriting patch files). The tool itself has a verification mechanism and will load only after the module is successfully verified at startup, but for security reasons, please be sure to download and use it from the official site.

# Function introduction

1. Support creating hijacking and injecting patches to achieve cracking without modifying the target file
2. support for patching processes with dynamic base addresses (ASLR)
3. support patching multiple DLL modules of the target process
4. Support patching different EXEs of the same patch
5. support patching the memory data of a process at a specified address
6. support for patching processes using feature code matching
7. support setting API HOOK decoding for shelled programs before patching data
8. support patching data after setting hardware breakpoint interrupt for the process
9. support setting exception breakpoints to modify the memory pointed to by registers or registers after interrupting the process
10. support setting conditional breakpoints for processes to determine whether to execute Patch according to the number of interrupts, register or memory values
11. Support setting different conditional breakpoints for the same address to perform Patch on the interrupts that meet the conditions
12. support extracting global variables from assembly instructions to store and modify them
13. support for storing data and using stored data during process execution
14. support patching the memory pointed to by the memory marker after interrupt
15. support basic operations on data after interrupt
16. support for reading patch data from ini file
17. support to create memory keymaker
18. support for creating debug patches to troubleshoot patch problems by yourself

Unpack password：www.chinapyg.com


## Screenshots-main

<img src="https://github.com/sicaril/Baymax-Patch-toOls/blob/main/pic/11.png"/>
<img src="https://github.com/sicaril/Baymax-Patch-toOls/blob/main/pic/12.png"/>
<img src="https://github.com/sicaril/Baymax-Patch-toOls/blob/main/pic/13.png"/>

## Screenshots-toOls
<img src="https://github.com/sicaril/Baymax-Patch-toOls/blob/main/pic/Compare%20en.png"/>
<img src="https://github.com/sicaril/Baymax-Patch-toOls/blob/main/pic/Hex%20en.png"/>
<img src="https://github.com/sicaril/Baymax-Patch-toOls/blob/main/pic/Search%20EN.png"/>
<img width="809" height="654" src="https://github.com/sicaril/Baymax-Patch-toOls/blob/main/pic/Translate-en.png"/>


