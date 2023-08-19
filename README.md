# Rhea

A tool for verifying constant time discipline of C/C++ implementaitons.

Rhea takes LLVM IR as input. It conducts several analysis on LLVM IR and boogie IR.

Rhea contains several modules:

- Smacks serves as a translator from LLVM IR to Boogie IR.
- Phasar functions as a framework for IFDS analysis.
- SVF provides precisely context-, flow-, and field-sensitive pointer analysis.
- Bam-bam-boogieman implements several productions on boogie IR.

Please contact songfu@shanghaitech.edu.cn or cailw@shanghaitech.edu.cn to obtain the password for the zip file.
