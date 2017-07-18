# LLVM
A build script for building the latest version of LLVM, Clang, Clang-tools, LLD, Polly, libc++, libc++ ABI, &amp; Compiler-RT 

Building Clang is a bit of a pain - this repository contains a bash script to make the process easier. Make sure that you have 
  GNU Make 	3.79, 3.79.1 	Makefile/build processor
  GCC 	>=4.8.0 	C/C++ compiler
  python 	>=2.7 	Automated test suite
  zlib 	>=1.2.3.4 	Compression library

and then source the provided install.sh script to build LLVM, Clang, Clang-tools, LLD, Polly,libc++, libc++ ABI,  &amp; Compiler-RT and place the executables in the bin directory under the build folder. You can either add said bin directory to your path &amp; ld_library_path or execute `make install` to put the build bbinaries and libarries in the right places in your system (be warned that since this is a pre-release, this is probably a bad idea).
