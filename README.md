# CBT800
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. GitHub repos will be deleted and created during this period...

```
//***FILE 800 is an extremely valuable contribution from Enrico     *   FILE 800
//*           Sorichetti and contains a RECEIVE/UNXMIT tool that    *   FILE 800
//*           works on a PC.  I am just offering Enrico's zip       *   FILE 800
//*           file here, because the programs are PC REXX programs  *   FILE 800
//*           and they are not for MVS use, directly.               *   FILE 800
//*                                                                 *   FILE 800
//*           You should download the ZIP member of this file to    *   FILE 800
//*           a PC in BINARY (no translation!) and unzip it on the  *   FILE 800
//*           PC.  Since I am not knowledgeable in this area, I'd   *   FILE 800
//*           suggest that you email Enrico if you have any         *   FILE 800
//*           questions.  (SG - 2008/12/19)                         *   FILE 800
//*                                                                 *   FILE 800
//*           email:  Enrico Sorichetti <e.sorichetti@alice.it>     *   FILE 800
//*                                                                 *   FILE 800
//*           NEW version is member ZIP     (see member $$NOTE2)    *   FILE 800
//*           OLD version is member ZIPOLD                          *   FILE 800
//*                                                                 *   FILE 800
//*    - - - - - - - - - - - - - - - - - - - - - - - - - - - - -    *   FILE 800
//*                                                                 *   FILE 800
//*    Short Summary and Description -                              *   FILE 800
//*                                                                 *   FILE 800
//*      As promised, I am sending you the result of my work.       *   FILE 800
//*      This is a zip file with the receive/unxmit REXX.           *   FILE 800
//*                                                                 *   FILE 800
//*      The main program, (it can be renamed in any way you        *   FILE 800
//*      like) and three subroutines... unzip them somewhere in     *   FILE 800
//*      your path.  A quick and dirty EBCDIC display tool and      *   FILE 800
//*      the license info.                                          *   FILE 800
//*                                                                 *   FILE 800
//*      It works only wih object rexx , until they fix Regina      *   FILE 800
//*      REXX...  A long time ago I found a bug in Regina rexx      *   FILE 800
//*      which prevents any useful utilization, ( I need to         *   FILE 800
//*      issue a MKDIR, ..... )                                     *   FILE 800
//*                                                                 *   FILE 800
//*      - after issuing a system command, the input file           *   FILE 800
//*        position is lost                                         *   FILE 800
//*      - it might be a mac/linux only issue, not tested on        *   FILE 800
//*        windows                                                  *   FILE 800
//*                                                                 *   FILE 800
//*      All the tests have been done on a mac and windows.         *   FILE 800
//*      On windows not exhaustive as on the mac (just a few        *   FILE 800
//*      selected files)                                            *   FILE 800
//*                                                                 *   FILE 800
//*      The only issue with windows is the lack of the             *   FILE 800
//*      mac/linux globbing so under windows it can be used only    *   FILE 800
//*      on single files.  For multiple (masked) files, a do        *   FILE 800
//*      works well.                                                *   FILE 800
//*                                                                 *   FILE 800
//*      On unix_like .... &RECEIVE *.XMI                           *   FILE 800
//*      On windows   .... for %i in ( *.xmi ) do; &RECEIVE %i      *   FILE 800
//*                                                                 *   FILE 800
//*     I have successfully received all, repeat ALL, the CBT       *   FILE 800
//*     XMI tapes base,updates,overflow,overflow updates,jes2       *   FILE 800
//*                                                                 *   FILE 800
//*     - more than 1200 xmi files, more than 70000 files/members   *   FILE 800
//*                                                                 *   FILE 800
//*     and checked also that ALL the inner XMI members of all      *   FILE 800
//*     the tapes were &RECEIVABLE, at least those whose names      *   FILE 800
//*     did not contain the $ char.                                 *   FILE 800
//*                                                                 *   FILE 800
```
