# Abstract

This set of scripts lets you manage overly complex [svn:externals](http://svnbook.red-bean.com/en/1.0/ch07s03.html) configurations.

# Use Case

You have many sub-repositories and a main directory with externals definitions pointing to these sub-repositories. You want to create the same branches and tags in all your sub-repositories.

It doesn't make any sense, but I'm required to work like this on a project.

## Limitations

It's completely untested if you use external definitions with a revision specified.

When you execute a `copy` operation the externals definitions aren't updated accordingly.

# Disclaimer

If you need these scripts, **you're in serious troubles**. You should urgently rethink the way your code is organized.

A more [modern SCM](http://git-scm.com) will also greatly improve the way you work.

However, if the choice isn't yours, feel free to use them. You can even improve them and send me a pull request. If I'm in a good mood, I'll merge it !
