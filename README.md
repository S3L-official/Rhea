# Rhea

A tool for verifying constant time discipline of C/C++ implementaitons. 

Rhea takes LLVM IR as input. It conducts several analysis on LLVM IR and boogie IR.

Rhea contains several modules:

- smacks serves as a translator from LLVM IR to Boogie IR.
- Phasar functions as a framework for IFDS analysis.
- SVF provides precisely context-, flow-, and field-sensitive pointer analysis.
- bam-bam-boogieman implements several productions on boogie IR.
