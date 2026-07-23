# Ada 2022 Standard Atomic Operations Packages

This project supplies the GNAT source files for the Ada 2022 language-defined units for atomic operations: System.Atomic_Operations, System.Atomic_Operations.Exchange, System.Atomic_Operations.Modular_Arithmetic, and System.Atomic_Operations.Integer_Arithmetic.

They are provided for use with those bare-board GNAT runtimes that do not (yet) include them, for example Arm-elf. 

The sources here are verbatim copies taken from a GNAT native runtime. As such, the implementations are GNAT-specific so their use with other compilers will not work. Howerver, they are not dependent on a specific version of GNAT, unlike regular runtime files.

Once the shipped GNAT runtimes include them you can simply remove any references to this project.
