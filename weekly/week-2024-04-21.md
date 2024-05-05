# Meeting minutes

- Time: 2024-04-21 15:00 - 15:40
- Participants: Cedric, Frozen, Zisu

# Topic: Cell Script R&D progress synchronization

# Content

## Goal achieved

- Basically complete the language grammar design and modification
- Mostly complete language features
- Considering introducing functional programming, improve function priority to become a first-class citizen

## Discussion

- Is data encoding and decoding required?

Cedric: Starting from the actual contract development, there is no need to use molecules for encoding and decoding. Decoding can be done directly in the contract code. There is no need to force the use of a certain design standard.

Frozen: Args and Cell Data need to be described through metadata to facilitate data expression and encoding and decoding. It is currently believed that the format of Cell Data is unified within the scope of the contract and does not present diversity.

- Is Molecule retained in standard library?

Frozen: Keep Molecule as a built-in system standard library, while providing a simplified version, removing complex structures, and using table-compatible structs.

Cedric: Vector and Array also use a similar approach, providing simplified versions.

- Meeting synchronization time?

Every Sunday at 11pm

## Plan for next week

- Large number processing
- xUDT required capabilities
- Standard library design
- Molecule is built into the standard library
- Collaborated with the CKB core team on debugger implementation and mock tool implementation

## TODO

Cedric - Advance standard library design as planned
Frozen - Organize the co-learning outline based on the problems encountered in Cell Script development, and seek help from Jan
Zisu - Organize co-learning

## Question

- Contract version management, compatibility processing and package management
