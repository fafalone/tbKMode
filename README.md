# tbKMode
twinBASIC Kernel Mode Support Package

This is a very preliminary effort to supply a package like WinDevLib, but for kernel mode programming in twinBASIC. At this stage, it's extremely preliminary, with only enough coverage to support my public HelloWorldDriver and a few additional projects I'm working on. If you make additions, please help out and submit them to be merged. 

**Updated 30 May 2025 (Version 0.2.4)** - Modest expansion focusing mainly on fltmgr for an upcoming project.

------------------------------

tbKMode
Windows Kernel Mode Definitions for twinBASIC
Ported by Jon Johnson (fafalone)

Includes structs, enums, macros, and APIs from wdm.h, mountmgr.h, and other kernel mode driver headers
This is *not* intended to be complete right off (wdm.h alone is nearly 50,000 lines!), rather expanded 
by each project using it then used as a start for the next. If you substantially expand this module, 
please submit an update! 

At this very early stage, there's very little coverage of a truly massive API surface area, but it 
can support a few small projects, and will give you ideas about how to adapt the very unfriendly
kernel mode code, which is very heavy on macros.

 
