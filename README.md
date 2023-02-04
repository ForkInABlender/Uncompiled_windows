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
* Windows-10/11 installed

# What is the point/goal here?

To reuse with unicorn-engine, nasm, python3-ctypes & python3-cython types, and bits of windows even on non-windows systems.
 The point is to have code that runs almost anywhere in and on any system including windows.
In this case, the point is to run windows software on almost any system without compiling or using wine. I'm talking about
 just using unicorn-engine, python, nasm, lambdas, keystone-engine, and python functions to imitate the windows kernel
  enough to load a binary library and use its functions without uncompiling and recompiling for each platform. Most of this
 is to make the windows kernel a little more python like. 

https://docs.binary.ninja/dev/bnil-overview.html#summary
https://kalkicode.com/c-to-golang-converter-online
https://kalkicode.com/go-to-python-converter
https://chat.openai.com/
https://www.javainuse.com/java2py
