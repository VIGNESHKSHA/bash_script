# git bash script
Git + VS Code automation from the terminal

`gitdev` is a small Bash CLI tool that speeds up your daily developer workflow by automating repository setup

**What it does**
When you run `gitdev`, it can;
- create a project directory
- clone a git repository
- track a remote branch and checkout
- Condition to check and open the project in the VS code
No more repetitve setups steps.

**Installation**
1. Move the script into personal bin folder

<pre>
    mv gitdev ~/bin/
    chmod +x ~/bin/gitdev
</pre>
   
3. Restart Git Bash

Now you can run:
<pre>
  gitdev
</pre>
from anywhere.

**Usage**
<pre>
  gitdev -d <directory>
  gitdev -dir <directory>
</pre>
You will be prompted to enter:
- Repository URL or `git clone` command
- Branch name to checkout

**Requirements**
- Git Bash(windows)
- Git installed
- VS Code
