**Note**:

The sources here are not directly executable. I completed the lab in sub-directories (lab/lab2, lab/lab3, etc.) respectively and copied the modifed files back to the lab/ directory, but some logistic files in lab/ remains the same.

This non-intuitive arrangement is caused by the fact that if I want to move on to another lab, I would have to excute commands like `git checkout -b lab3 origin/lab3`, but the `origin` of `lab/` is already set to this repository, thus that command won't work. The work-around I used, is to clone the original git repo to a subdirectory (eg. lab/lab2), run the lab there, and then copy the modified files to this repository.
