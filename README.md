```
$ alias gelp="git_commit_helper"
$ gelp -h
Usage: git_commit_helper [options]
    -m, --merge [<branch>]           Merge to branch after committing
    -c, --checkout [<name>]          Checkout to new branch before committing
    -s, --squash                     Squash all selected commits
    -p, --push                       Pushes the given changes
    -u, --upstream                   Performs the selected action upstream. Works with push and delete.
    -d, --delete [<branch>]          Removes the given branch locally
    -a, --all                        Adds all local changes
    -h, --help                       Displays Help
```
