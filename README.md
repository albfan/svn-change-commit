# svn-change-commit
Update svn commit messages easily from svnadmin

##Installation

Download and symlink to your path

```bash
$ git clone https://github.com/albfan/svn-change-commit.git
$ cd svn-change-commit
$ ln -s $PWD/svn-change-commit ~/bin/
```

#Usage

From svn repo do:

    $ svn-change-commit -r $HOME/projects/svnrepo -n265 "New message\n\nfixes#532"
