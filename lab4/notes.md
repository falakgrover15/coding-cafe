## Question 1
The `--global` option in `git config` saves a setting for all Git repositories belonging to my user account. Without `--global`, the setting applies only to the current repository.

## Question 2
The `ls -a` command shows hidden files and folders, including `.git`. The `.git` folder contains Git's internal information, such as commit history, configuration, and repository data.

## Question 3
Git was offering to track the files in my project that were not already tracked or ignored. The `.venv/` folder contained files I did not write myself, so I needed to exclude it using `.gitignore`.

## Question 4
After creating `.gitignore` with the specified patterns, the `.gitignore` file appeared under Untracked files, while `.venv/` no longer appeared in the status output. This showed that Git was ignoring the files and folders matching those patterns.

## Question 5
The `.gitignore` file should itself be committed because it tells Git which files other contributors should ignore. It should not be ignored because everyone working on the repository needs access to the same rules.

## Question 6
When I ran `git add README.md`, the file moved into the Changes to be committed section of `git status`. In the three-stage model, its contents were added to the staging area, ready for the next commit.

## Question 7
My commit printed `2 files changed, 4 insertions(+)` and created `.gitignore` and `README.md`. When I later tried to commit with the message `Lab work so far`, Git reported that there was nothing to commit because there were no new changes.

## Question 8
The first seven characters of my first commit hash are `1b3875e`. They are an abbreviated identifier for the commit, allowing me to refer to it without typing the entire hash.