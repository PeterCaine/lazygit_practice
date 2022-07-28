# lazygit_practice
lazygit_practice

## take 2
take one issues: incorrect credentials:
solution is to ssh when cloning


# issues

## pushing incorrect changes
- how to retreive an incorrectly pushed file:
  1. open a draft pull request
  2. see the file and panic
  3. move the file from local repo (same branch - put in dir out of the way - rename 'amended_file.ext')
  4. push the deleted file change
  5. checkout previous commit where original unamended file is present
  6. copy that file also into the out-of-the-way-dir
  7. checkout the branch you just pushed where file is missing
  8. move the original file just moved (not amended) back into branch
  9. push again
  10. open a proper pull request
