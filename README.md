# HugeFileDiffLines
Utility to compare two huge text files and generate files with only the differences

Need to make this more user friendly, but basically it will accept two text files, compare them line-by-line, and spit out two output files, with only the lines that are not identical.

You can run these output files in [ExamDiff Pro](https://www.prestosoft.com/edp_examdiffpro.asp) (my favorite diff tool) or your favorite diff tool, and see the differences without trying to load these entire files into memory. It may or may not work the way you expect, depending on how different the files actually are.
