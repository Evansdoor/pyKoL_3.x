# pyKoL_3.x
A [python 3.x](https://www.python.org/) package for interacting with the game [The Kingdom of Loathing](https://www.kingdomofloathing.com/).

## Introduction
This is a total rewrite of the python 2.7 https://github.com/scelis/pykol that has been abandoned since 2014.

This rewrite is to:
1. Update code to run under python 3.x.
1. Make all code PEP-8 compliant.
1. Try and maintain call functionality with the original calls, where possible.

It is licensed under the [BSD-3-Clause license](https://opensource.org/licenses/BSD-3-Clause).

## What is it?
A general purpose package to make it easy to automate functions in the game [The Kingdom of Loathing](https://www.kingdomofloathing.com/). 

## Who is it for?
pykol is for programmers who are interested in writing scripts and bots for KoL. If you do not feel comfortable writing code, then pykol is probably not for you. If you are after account automation for interactive usage please look at [Mafia](http://kol.coldfront.net/thekolwiki/index.php/Tools#KoLmafia).

## Requirements
Only [python 3.x](https://www.python.org/) and it's standard libraries (obviously).

## How can I contribute?
1. [Fork](https://help.github.com/articles/fork-a-repo/) pyKoL_3.x
1. Clone your fork with `git clone git@github.com:your_username/pyKoL_3.x.git`
1. Add a remote to this repository with `git remote add upstream git://github.com/evansdoor/pyKoL_3.x.git`
1. Fetch the current pykol sources with `git fetch upstream`
1. Create a topic branch with `git checkout -b my_branch upstream/master`<br>where "my_branch" can be any name you want.
1. [Commit](https://git-scm.com/docs/git-commit) (or [cherry-pick](https://git-scm.com/docs/git-cherry-pick)) your changes.
1. Push your branch to github with `git push origin my_branch`
1. Create an [Issue](https://github.com/Evansdoor/pyKoL_3.x/issues) with a link to your branch.<br>**That's it!**

## Example Code
The following is some example code that demonstrates how to login to The Kingdom of Loathing, grab the contents of your inbox, access the item database, as well as to pull, use and smash items.

`To be done when the code is actually running!`

Will use the equivalent example from the original repository.

## Running the Unit Tests.
Unit tests still being updated....

pykol includes a unittest suite, to showcase some of its functionality and to help ensure that new game changes don't break your existing code. Developers are strongly encouraged to add unit tests for new features that they create.

To run the test suite:

## Major fixes
1. Code update for the move of KoL to HTTPS now working.
2. Regexes update for the move to [AWS](https://www.aws.com/) now working for tested calls.

## Current Issues
1. No upload of files yet.
1. Unit tests run. Yippee!
1. data/Patterns.py still being updated to use ' instead of " and loosen up the regexes. As they currently stand the older regexes break on any CSS change. This will still be an issue after my first code commit.
1. Update data/Adventures.py to be in sync with Mafia.
1. Created data/Character.py for character and account based variables, such as class, levels and main stats.
1. Updating data/Quests.py for many, many missing quests.
1. Still need to update data/[Skills|Items].py 

## Current Roadmap
I'll upload an initial code base sfter:
1. the data directory is finished, except for Patterns.py, and
2. an updated example from scelis' git hub page works, and
3. the current unit tests are updated to cover the example code.
