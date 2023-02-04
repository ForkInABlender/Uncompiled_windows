# This is an uncompiled version of windows.

Most of the binaries Windows OS uses will be picked apart for the purposes of reverse engineering. Binary ninja is very
 reliable as a decompiler and has provided more than likely usable code that needs some retooling. Other than being mindful
  of the tools' developers' artifacts, it should run without any issue. You may find you're missing something, and the
 runtime should tell you where or what to look for, or place things that are needed. The hints will be available as you
  pen test, reverse engineer, or write templates to reduce the time spent rewriting code by hand.

# What is required to reverse engineer compiled windows code?

* Binary Ninja to be downloaded. "Installed" is subjective to where the folder is extracted to
* python3.8 or better
* WSL2 ubuntu18 or better
* understanding of how to use unicorn-engine, keystone-engine, cygwin, nasm, ctypes, binary, assembly & c/c++ code with python3 code
* Windows11 installed

https://docs.binary.ninja/dev/bnil-overview.html#summary
