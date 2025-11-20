# Caleb Preece-Oughton

**Software Engineering Undergraduate**
Focus: Windows Internals, Kernel Development, Reverse Engineering.

---

### Projects

**[Kernel Process Management Engine](https://github.com/1vrx/vrxAim)**
*Windows Kernel-Mode Driver (C++)*  
A WDK driver implementing undocumented process management techniques.
* **Core Functionality:** Direct Kernel Object Manipulation (DKOM) of `EPROCESS` and `KTHREAD` structures.
* **Key Features:** Implemented custom thread management and memory protection bypasses to explore kernel-user boundaries.

**[PE Viewer](https://github.com/1vrx/PEViewer)**
*Binary Analysis Tool (C++, ImGui)*  
A manual parser for the Portable Executable (PE) format, built to analyze Windows binaries without external parsing libraries.
* **Core Functionality:** Parses DOS/NT headers and Data Directories to enumerate Imports (IAT) and Exports.
* **Visualization:** Maps the relationship between file offsets and Virtual Memory addresses (RVA/VA) to visualize loader behavior.

**[Driver Security Analysis](https://github.com/1vrx/kdfork)**
*Vulnerability Research*  
* Reverse-engineered a vulnerable third-party driver to identify functions that enable arbitrary physical and kernel memory access.
* Refactored a popular driver mapper (kdmapper) to support custom driver functionality and bypass standard allocation checks.

---

### Technical Competencies

* **Languages:** C, C++, x86-64 Assembly, Python
* **Debuggers:** WinDbg, x64dbg
* **Analysis:** IDA Pro, ReClass
* **Interests:** Rootkit development, Anti-Cheat analysis, OS internals

---

[caleb.po@outlook.com](mailto:caleb.po@outlook.com) 
