# Exercise6_pSet1_AI_TUC



This exercise attempts to solve cryptarithmetic puzzles using CSP solvers.

Currently only works with Backtracking Strategy, others may be implemented as time passes.

Main Class is named Main, for compiling and executing purposes.

The general command in order to execute the file is this one below, ran inside the project folder.

javaw.exe -Dfile.encoding=Cp1252 -classpath "<PATH_TO_PROJECT_FOLDER>\bin" -XX:+ShowCodeDetailsInExceptionMessages mainPackage.Main <YOUR_ARGUMENTS HERE>



To see a small description of which files implemented by me and which were found in online sources, which i mention on my report
you can run the program with arguments "-d"

To run the solver all you need to do is run the program with arguments "-s <# of problem to solve>. For example, by specifying arguments as "-s 1" the solver will attempt to solve
the first puzzle.


Problems number 1 and 2 work correctly, while there's some more work that need to be done for problem 3 so attempting to solve it will end up returning a NULL assignment path.

For example, a full command shown that solves the first puzzle has this form right here :
$ javaw.exe -Dfile.encoding=Cp1252 -classpath "<PATH_TO_PROJECT_FOLDER>\bin" -XX:+ShowCodeDetailsInExceptionMessages mainPackage.Main -s 1.

Same goes on for the rest of the arguments.
