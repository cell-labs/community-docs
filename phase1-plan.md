# meeting minutes

- Time: 2024-04-06 01:10 - 02:35
- Participants: Cedric, Frozen, Zisu

# Topic: Cell Script’s recent plans for continued development

# content:

## Cell Script continues to advance
Cedric will work full-time on the research and development of Cell Script; Frozen will organize, coordinate resources, and participate in part of the research and development work; Zisu will participate in part of the research and development work

## Cell Script Phase 1 R&D Plan

The goal is to implement xUDT using Cell Script and push the language to the community

### 1. Language design
a. Grammatical style
- Currently refer to the Golang syntax style for adjustments and promote research and development work;
- Control statements, loop statements, type postfixes, function declarations

b. Language features
- unsigned data type
- Memory control
- error handling
- Paradigm (to be determined)
- Reflection (not supported)

c. Runtime limit (delay)
- Function recursion, nesting level
- Memory usage
- Program BIN file size

### 2. Standard library design
a. Molecule decoding
b. Capabilities used by xUDT

### 3. Debugger
a. Integrate ckb debugger with llvm capabilities to implement debugging
b. Integrated into a tool

### 4. Toolchain

4.1 Cell Script Toolchain
- Compiler
- deploy cli

4.2 CKB Mock Toolchain
- Mock Tx
-Dump Tx
- Simulation environment management

Expected development cycle: **8 weeks**

#### Required resources
- CKB provides consulting and assists in standard library and toolchain design and development
