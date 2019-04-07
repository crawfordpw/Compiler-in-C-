# Compiler-Theory
Compiler written for the University of Cincinnati class EECE6083: Compiler Theory and Practice. The goal of this project is to build a simple recursive descent LL(1) compiler by hand (not using compiler construction tools such as flex or antlr) utilizing the C++ programming language and a simple C file format for code generation. The language to be compiled is given in the specification PDF defined by Dr. Wilsey for the 2016 Spring semester. The final output simple C format is meant to closely replicate a 3-address load/store architecture.

The project can be organized into 5 seperate developmental phases. The scanner, parser, type checking, code generation, and runtime environement. The file titled "project.pdf" goes into much more detail of what is required for each of these 5 phases phase. Another useful file to look into is "projectLanguage.pdf". This file includes all of the necessary syntax, language semantics, builtin functions to be implemented, and additional comments on the programming language. 
