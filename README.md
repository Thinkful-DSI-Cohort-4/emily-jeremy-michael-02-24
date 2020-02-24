# emily-jeremy-michael-02-24
Answers to questions

> How do you see the files changed within each commit using GitHub Desktop GUI?

Select the target repository, and select the "Changes" tab to view changed files. Alternately, using the command line, sing the `git status` or `git log` commands.

> How do you see the contents of what changed within each file for a commit?

On the command line, you would type `git diff <filename>`
In the GUI, you'd have the file selected and you'd be inside the Changes tab.


> How do you revert (backout) a commit?

using command line type `git reset --hard HEAD~(number of steps back you want to go)` or `git reset <the-sha-of-that-commit>`

> What does HEAD refer to in the context of git?

HEAD is the commit that Git is currently pointing to.

Changing file here.
