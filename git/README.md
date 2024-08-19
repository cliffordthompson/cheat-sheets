|Command	|Flag	|Parameters	|Description|
|---|---|---|---|
|git add 	|-i	|[\<pathspec\>]	|Enter Interactive Add Mode|
|git add 	|-p	|[\<pathspec\>]	|Enter Interactive Patch Mode|
|git am	|	|\<dir\>	|Apply formatted patches in \<dir\>|
|git apply	|	|[\<patch\>]	|Apply a patch file to the workspace|
|git apply	|-R	|\<patch\>	|Apply a inverse of a patch file. Does not reverse the removal of files.|
|git blame	|	|\<filename\>	|Browses an annotated version of \<filename\>|
|git blame	|-w	|\<filename\>	|Browses an annotade version of \<filename\>, but ignore whitespace changes|
|git blame	|-L	|\<line1\>,\<line2\> \<filename\>	|Browses an annotated version of \<filename\> between \<line1\> and \<line2\>|
|git blame	|	|\<commit\> [--] \<filename\>	|Browses an annotated version of a file at \<commit\>|
|git branch	|--contains	|\<commit\>	|Show the branches that contain \<commit\>|
|git branch	|--no-contains	|\<commit\>	|Show the branches that don't contain \<commit\>|
|git checkout	|	|- b \<branch\> \<commit\>	|Create a branch \<branch\> starting a \<commit\>|
|git checkout	|	|- 	|Switch to the previous branch|
|git checkout	|-m	|\<branch\>	|Locally renames the current branch to \<branch\>|
|git checkout	|-m	|\<old branch\> \<new branch\>	|Locally renames \<old branch\> to \<new branch\>|
|git cherry-pick	|	|\<commit\>[..\<commit\>]	|Cherry Pick Commit (or Range)|
|git cherry-pick	|--continue	|	|Continue Cherry Pick after resolving conflicts|
|git cherry-pick	|--abort	|	|Abort a cherry pick with conflicts|
|git commit	|-a	|	|Commit all tracked files|
|git commit	|-m	|\<msg\>	|Commit staged files with the commit message in \<msg\>.|
|git commit	|--amend	|	||
|git diff	|--name-only	|\<commit\>[..\<commit\>]	|Show files changed in commit (or range)|
|git diff	|--cached	|	|Show the file diff for the staged files.|
|git diff	|--name-only	|\<branch\> $(git merge-base \<branch\> \<parent-branch\>)	|Find the files that changed in \<branch\> since it branched from \<parent-branch\>|
|git diff	|--name-only	|\<start commit\> \<end commit\>	|Find the files that changed between \<start commit\> and \<end commit\>|
|git diff	|-w	|	|Do not show whitespace changes|
|git diff	|--color-words	|	|Only colour the word differences, rather than the entire line|
|git diff	|--color-words=.	|	|Only colour the character differences, rather than the entire line|
|git diff	|-G	|\<regex\>	|Look for differences in unstaged changes that match \<regex\>.|
|git diff	|--cached -G	|\<regex\>	|Look for differences in staged changes that match \<regex\>.|
|git diff	|	|\<commit\>^..\<commit\> -- \<file\>	|Show changes to \<file\> between commits|
|git fetch	|-p	|	|Fetches from the remote and prunes deleted remote branches|
|git format-patch	|	|-o \<dir\> [ \<since\> | \<revision range\> ]	|Create Unix mailbox-formatted patches and place them in \<dir\>|
|git log	|--oneline	|	|Show commits using a single line per commit|
|git log	|--graph	|	|Show commits with a merge graph|
|git log	|(-p | --patch)	|	|Show the diffs along with the commits|
|git merge-base	|	|\<branch\> \<branch\>	|Find the common ancestor for two branches.|
|git merge-base	|--is-ancestor	|\<maybe commit\> \<commit\>	|Returns success if \<maybe commit\> is an ancestor of \<commit\>|
|git pull	|-p	|	|Fetches & Merges from the remote and prunes deleted remoted branches|
|git pull	|--rebase	|	|Fetches and Rebases the remote version of the branch|
|git rebase	|	|\<upstream\> [\<branch\>]	|Rebase \<branch\> onto \<upstream\>|
|git rebase	|-i	|\<upstream\> [\<branch\>]	|Perform an interactive rebase of \<branch\> onto \<upstream\>|
|git rebase	|--onto	|\<newbase | commit\> \<upstream\> \<branch\>	|Rebase \<branch\> on \<newbase\> from the common ancestor of \<upstream\> and \<branch\>. \<newbase\> |
|git rebase	|--continue	|	|Continue Rebase after resolving conflicts|
|git rebase	|--abort	|	|Abort a rebase with conflicts|
|git rebase	|--skip	|	|Skip a commit while resolving conflicts|
|git reset	|--hard	|ORIG_HEAD	|Undo a rebase by resetting HEAD back to ORIG_HEAD.|
|git show	|	|\<commit\>[..\<commit\>]	|Show a diff of a commit (or range)|
|git rm	|--cached	|\<filename\>	|Remove a file from staging but leave the file changes in the workspace|
|git shortlog	|-s -n --all	|	|Show number of commits for all users across all branches. Merge commits are considered.|
|git shortlog	|-s -n --all --no-merges	|	|Show number of commits for all users across all branches. Merge commits are ignored.|
|git shortlog	|-s -n --all --	|\<filename\>	|Show number of commits for all users across all branches for \<filename\>. Merge commits are considered.|
|git shortlog	|-s -n --all --no-merges --	|\<filename\>	|Show number of commits for all users across all branches for \<filename\>. Merge commits are ignored.|
|git ls-files	|	|	|Show all tracked files recursively from the current repository directory.|
|git stash	|	|	|Creates a stash using the staged and unstaged changes, and rolls back to HEAD|
|git stash	|--keep-index	|	|Creates a stash using the staged and unstaged changes, but leaves the changes in the working directory|
|git stash show	|-p | --patch	|\<stash\>	|Shows a patch of the changes in a stash|
|git reset	|	|\<filename\>	|Removes changes to \<filename\>, but does not affect the workspace|
