# Operating-system-Project

Phase 1 of OS Project
This repository represents Phase 1 of an Operating System (OS) project. In this phase, we've implemented fundamental OS components, including memory management, input/output operations, and instruction execution. Here's a concise overview of the core functionalities:

1. Memory Management
A 100x4 physical memory (M) is used for storing data and instructions.
2. Input/Output Operations
Read Mode (SI=1): Reads data from an input file into memory.
Write Mode (SI=2): Writes data from memory to an output file.
Terminate (SI=3): Closes the output file, marking program completion.
3. Instruction Execution
The Execute function simulates instruction execution by fetching, interpreting, and executing instructions from memory.
4. General Purpose Register
A general-purpose register (R) is used for temporary data storage.
5. Conditional Branching
Conditional branching using the Condition (C) flag allows branching to specified instructions based on the flag's value.
6. Loading Programs
The LOAD function reads program instructions and data from an input file, recognizing program sections using control cards like "$AMJ" (job start), "$DTA" (data section start), and "$END" (job end).
7. Initialization
The OS class initializes memory and registers to zero values upon creation.
