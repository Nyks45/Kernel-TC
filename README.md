                                   X86_64-GCC-Linaro-5.4.0 
                                       android
                                cross-compile toolchain

RUN ./setup to set up the toolchain for use. Requires tar with x filter support.

The excluder of this TC has been compressed with tar with x filter & split due to upload errors by git client.

TC for x86_64 architecture for kernel compilation, compiled from Linaro GCC 5.4.0 source with graphite, Custom GSR, and link-time optimizations(to).

This TC has embedded Newlib C library support with plugin & to optimizations along with custom CLoog, PPL & GDB code support.


                            setup export commands in .bashrc

                                 export ARCH=x86_64
                            export CCOMPILE=$CROSS_COMPILE
                         export CROSS_COMPILE=x86_64-Linux-
                           and your toolchain path...
                          
                                   Enjoy Compiling
