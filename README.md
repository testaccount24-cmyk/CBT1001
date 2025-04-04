# CBT1001
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. GitHub repos will be deleted and created during this period...

```
//***FILE1001 is from Peter Vels and contains some nice REXX        *   FILE1001
//*           execs.  Three of them are for illustrative purposes   *   FILE1001
//*           and they show you how to produce very nice images     *   FILE1001
//*           on the screen, and the other 3 execs are VERY VERY    *   FILE1001
//*           USEFUL.                                               *   FILE1001
//*                                                                 *   FILE1001
//*       Instructions are in the $README member.                   *   FILE1001
//*                                                                 *   FILE1001
//*       email:  Peter Vels <peter.vels@gmail.com>                 *   FILE1001
//*                                                                 *   FILE1001
//*     DESCRIPTION OF CONTENTS:                                    *   FILE1001
//*                                                                 *   FILE1001
//*     The first 3 Rexxes can be invoked as TSO commands,          *   FILE1001
//*     e.g.  TSO FERNSIDE                                          *   FILE1001
//*                                                                 *   FILE1001
//*     PVCPUPCT.  Displays current CPU% in pseudo-graphical        *   FILE1001
//*       format.  Needs some simple customisation, such as         *   FILE1001
//*       supplying LPAR (system) names.  Do a FIND on "custom"     *   FILE1001
//*       to see where in the code things need to be                *   FILE1001
//*       customised.                                               *   FILE1001
//*                                                                 *   FILE1001
//*     MANDELBR - an ISPF implementation of displaying the         *   FILE1001
//*       Mandelbrot Set in 8 glorious colours.  Works best on      *   FILE1001
//*       62x160 screens.  Scrollable and zoomable.  Use PF19       *   FILE1001
//*       and PF20 to zoom in and out, and PF7, PF8, PF10 and       *   FILE1001
//*       PF11 to move up, down, left and right.  Still has         *   FILE1001
//*       bugs, so constructive feedback is welcome.                *   FILE1001
//*                                                                 *   FILE1001
//*     FERNSIDE - an ISPF implementation of the Barnsley Fern.     *   FILE1001
//*                Inspired by New York's Dan Shiffman.             *   FILE1001
//*                                                                 *   FILE1001
//*     All of the above are demonstrations of using ISPF           *   FILE1001
//*     dynamic areas with shadow variables which allow one to      *   FILE1001
//*     display characters of different colours right next to       *   FILE1001
//*     each other (i.e. it doesn't cost you an attribute byte      *   FILE1001
//*     - very nice).                                               *   FILE1001
//*                                                                 *   FILE1001
//*     The next 3 Rexxes are all edit macros.                      *   FILE1001
//*                                                                 *   FILE1001
//*     SYNTAX - a COBOL syntax checker (edit macro) which          *   FILE1001
//*         invokes the compiler and interleaves error messages     *   FILE1001
//*         right in your source code as notes.  Obviates the       *   FILE1001
//*         need to switch between an error listing and the         *   FILE1001
//*         source.  Instructions: While editing a COBOL program    *   FILE1001
//*         enter SYNTAX as a primary command. The first time       *   FILE1001
//*         you invoke SYNTAX you should also specify something     *   FILE1001
//*         (any character will do) as an argument, for example,    *   FILE1001
//*         SYNTAX P which will bring up the configuration panel    *   FILE1001
//*         where you can specify input required by the COBOL       *   FILE1001
//*         compiler.                                               *   FILE1001
//*                                                                 *   FILE1001
//*         Tip: To use the syntax checker iteratively:             *   FILE1001
//*         enter RES;SAVE;SYNTAX as a primary command.             *   FILE1001
//*         Note: There is a dependency on CBTTAPE File 452 for     *   FILE1001
//*               dynamic STEPLIB support.                          *   FILE1001
//*                                                                 *   FILE1001
//*     PVJCL - a Rexx edit macro which, when run while viewing     *   FILE1001
//*         unfamiliar JCL, displays the JCL formatted on an        *   FILE1001
//*         ISPF panel to make it easier to understand.             *   FILE1001
//*         Designed for those either not familiar with JCL at      *   FILE1001
//*         all or not familiar with a large JCL member.  Just      *   FILE1001
//*         makes it easier to understand.                          *   FILE1001
//*                                                                 *   FILE1001
//*     PVALLOCD -  a Rexx edit macro used in SDSF to display       *   FILE1001
//*         JESYSMSG allocations in a friendly format so that       *   FILE1001
//*         you can see what data sets were used by the job.        *   FILE1001
//*         Allows direct browsing of the data sets by cursor       *   FILE1001
//*         position.                                               *   FILE1001
//*                                                                 *   FILE1001
//*         Invoke PVALLOCD from within SDSF by entering the        *   FILE1001
//*         line command SE next to a job that has already run.     *   FILE1001
//*         It's more efficient to enter the SE after first         *   FILE1001
//*         entering a ? to display the various output DDs for      *   FILE1001
//*         the job.  Enter the SE line command on the JESYSMSG     *   FILE1001
//*         line.  Once you are editing the job output, enter       *   FILE1001
//*         PVALLOCD as a primary command to display the data       *   FILE1001
//*         set allocations.  You can browse the data sets by       *   FILE1001
//*         positioning the cursor anywhere on the name and         *   FILE1001
//*         hitting enter.                                          *   FILE1001
//*                                                                 *   FILE1001
//*     Copying and use of this material is allowed.  I retain      *   FILE1001
//*     ownership.  None of these routines may be sold. If you      *   FILE1001
//*     have error corrections or improvements I would be happy     *   FILE1001
//*     to hear from you.  If you use them or learn something       *   FILE1001
//*     from then I'd be even happier to hear from you.             *   FILE1001
//*                                                                 *   FILE1001
```
