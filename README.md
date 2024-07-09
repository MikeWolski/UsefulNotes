Useful Notes

For changing the git bash layout to a single line:
  Step 1. Create and edit a .bashrc file in the ~ directory.
  Step 2. Paste in the following: PS1="\[\033[32m\]\u@\[\033[35m\]$MSYSTEM:\[\033[33m\]\w\[\033[36m\]`__git_ps1`\[\033[0m\]$ "
  Step 3. Run source ~/.bashrc
