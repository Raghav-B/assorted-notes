https://ghidra.re/courses/GhidraClass/Beginner/Introduction_to_Ghidra_Student_Guide_withNotes.html#Introduction_to_Ghidra_Student_Guide.html

**What is Ghidra**
- IDE for Reverse Engineering (RE) tasks.
- Written in Java
- Has 5 major parts:
  - Programs
  - Plugins
  - Tools
  - Project Manager
  - Server
  
**What does Auto-Analysis do?**
- Starts at the executable code's entry points.
- Disassembles the executable code into instructions by following control flows.
- Creates functions at called locations (same as labels?)
- Creates cross references
  - https://resources.infosecinstitute.com/ida-cross-references-xrefs/#gref
  - Cross references help us determine where functions were called from or where a particular memory address was accessed. It even gives information on exactly *how* the information was accessed as well. Cross references can be code or data cross references. Code cross references talks about the location from where certain functions are called. 
