# Operating-system-Project

**Phase 1 of OS Project**

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


**Phase 2 of OS Project**


1. Memory Management and Allocation
Dynamic memory allocation for program sections and handling page faults for optimal memory use.
2. Advanced Error Handling
Enhanced error management with detailed error messages for "Out of Data," "Line Limit Exceeded," "Time Limit Exceeded," "Operation Code Error," "Operand Error," and "Invalid Page Fault."
3. Process Control Block (PCB)
Introduction of a Process Control Block (PCB) to manage program execution with attributes like job ID, Time To Live (TTL), Time Limit for Line (TLL), Time To Completion (TTC), and Time Line Counter (TLC).
4. Input/Output Operations
Improved Input and Output operations with dynamic page allocation and error handling.
5. Execution and Instruction Set
Expanded program execution cycle with a wider range of instructions, including conditional branching based on the Condition (C) flag.
6. Memory Map Visualization
Enhanced memory mapping for better visualization of memory allocation, page frames, and program sections.
Detailed output logs, memory maps, and error messages for comprehensive debugging and analysis.
