git study:
    git add file:Add modification from workspace to stage.

    git commit -m"commit": Commit modification from stage to branch.

    git log:Show commits log from recent to farthest ("--pretty=oneline" argument can make information clear).

    git reset --hard HEAD^:Rollback to particular version, "HEAD" means current version, "Head" followed by three "^" means the latest three versions. "HEAD~3" means the same.

    <!-- git reset HEAD <file>: Unstage modification back to workspace. -->

    git reflog:Show every command you do.

    git status:Show status about every file in stage.

    git restore <file>:Rollback file to last time you add or commit.

    git restore --stage <file>:Unstage modification back to workspace.
