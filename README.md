# takwira
takwira is a mobile app that lets you join a team for a football match or reserve a stadium for you and your friends

## Contributors
* Ghassen Ghabarou

* Ghassen Chaabouni

### Git feature branch workflow
The core idea behind the Feature Branch Workflow is that all feature development should take place in a dedicated branch instead of the master branch. This encapsulation makes it easy for multiple developers to work on a particular feature without disturbing the main codebase. It also means the master branch will never contain broken code

#### Useful git commands
Instead of using <b>git pull</b>
* git fetch origin/<i>remoteBranch</i>
* git merge origin/<i>remoteBranch</i> // merge into current branch

or
* git rebase origin/<i>remoteBranch</i> // similar to merge

##### P.S
You can't push directly to master, you need to push to a different branch then do a pull request
