# git-branch-case-bug
Intended to help diagnose, reveal, and test a filesystem-related case-sensitivity bug in git.

In particular, you may notice that this repo has two branches whose overlapping directory differs only by case: "bugfix/lower" & "BUGFIX/UPPER"... & "bugfix" != "BUGFIX".
