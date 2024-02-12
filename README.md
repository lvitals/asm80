This project is a fork of the Intel 8080 Assembler by Jay Cotton
and Claude Sylvain.

http://asm8080.sourceforge.net/

It was forked from the version 1.0.5 (from 6 January 2012). There are no
functional changes in the fork. I only added simple build scripts and
makefiles for Windows and Mac.

To build on Windows, start your Visual Studio command line prompt and:
   
    cd windows
    nmake
    
To build on Mac:

    cd mac
    make
    
Also, there is a bug fixed when the assembler didn't return non-zero
exit code on a complication error.
