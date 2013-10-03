git-stuff
=========

Stuff to help make everyday git'ing a bit more fun

git-completion.bash can be found here:
https://raw.github.com/git/git/master/contrib/completion/git-completion.bash

The interpreter line must be updated. Normally to `#!/bin/bash`

My local copy was fetched 25.05.2013

OS X
----

To get tab completion and gitprompt, you need this in your `.bashrc` or equivalent:

```bash
  GIT_PS1_SHOWDIRTYSTATE=true
  
  . /usr/local/sbin/git-completion.bash
  . /usr/local/sbin/git-prompt.sh
  
  export PS1='\[\033[01;32m\]\u@\h\[\033[01;34m\]:\w$(__git_ps1)\[\033[0m\]\$ '
```
