### General-Purpose Registers

| **64-bit** | **32-bit** | **16-bit** | **8-bit (Lower)** | **8-bit (Upper)** | **Description**                                       |
|------------|------------|------------|-------------------|-------------------|-------------------------------------------------------|
| RAX        | EAX        | AX         | AL                | AH                | Accumulator for arithmetic operations and I/O.       |
| RBX        | EBX        | BX         | BL                | BH                | Base register, often used for data access.           |
| RCX        | ECX        | CX         | CL                | CH                | Counter for loops and string operations.             |
| RDX        | EDX        | DX         | DL                | DH                | Data register, used for I/O and arithmetic operations.|
| RSI        | ESI        | SI         |                   |                   | Source index for string operations.                  |
| RDI        | EDI        | DI         |                   |                   | Destination index for string operations.             |

### Stack Register

| **64-bit** | **32-bit** | **16-bit** | **8-bit (Lower)** | **8-bit (Upper)** | **Description**                                       |
|------------|------------|------------|-------------------|-------------------|-------------------------------------------------------|
| RSP        | ESP        | SP         |                   |                   | Stack pointer, points to the top of the stack.       |

### Base Pointer Register

| **64-bit** | **32-bit** | **16-bit** | **8-bit (Lower)** | **8-bit (Upper)** | **Description**                                       |
|------------|------------|------------|-------------------|-------------------|-------------------------------------------------------|
| RBP        | EBP        | BP         |                   |                   | Base pointer, used to point to the base of the stack frame. |

### Instruction Pointer

| **64-bit** | **32-bit** | **16-bit** | **8-bit (Lower)** | **8-bit (Upper)** | **Description**                                       |
|------------|------------|------------|-------------------|-------------------|-------------------------------------------------------|
| RIP        |            |            |                   |                   | Points to the next instruction to execute.           |

### Segment Registers

| **64-bit** | **32-bit** | **16-bit** | **8-bit (Lower)** | **8-bit (Upper)** | **Description**                                       |
|------------|------------|------------|-------------------|-------------------|-------------------------------------------------------|
|            |            | CS         |                   |                   | Code segment, points to the segment containing executable code. |
|            |            | DS         |                   |                   | Data segment, points to the segment containing data. |
|            |            | SS         |                   |                   | Stack segment, points to the segment containing stack. |
|            |            | ES         |                   |                   | Extra segment, used for additional data segments.    |
|            |            | FS         |                   |                   | General-purpose segment register, often used for thread-specific data. |
|            |            | GS         |                   |                   | General-purpose segment register, often used for specific data storage. |
