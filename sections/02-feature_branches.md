# Feature Branches

When developers work on a project, _especially_ if they are working with others, they do not commit changes directly to the `main` branch. Instead, they work on separate **feature branches**.

All students should follow these next steps.

## Create a local feature branch

You should have the `github-workflow` repository cloned down and open in VS Code.

1. In the VS Code terminal, run this command to create a new branch, replacing `X` with your corresponding letter:\
   `git checkout -b feature-X`\
   For example, Student C would run `git checkout -b feature-C`.
   ![](/images/02-feature_branches/1.png)
2. Run `git status` or `git branch` to verify that you are now on the new feature branch.
   ![](/images/02-feature_branches/2.png)

> [!TIP]
>
> Using descriptive branch names will help you and your team stay organized! The name should reflect the changes that will be committed on that branch.

## Work on your feature

1. Open `README.md`. On line 3, write the following text as follows:
   1. Student A should write `To improve is to change.`
   2. Student B should write `There is nothing permanent, except change.`
   3. Student C should write `All that you change, changes you.`
2. Save your changes to the file.
3. Commit these changes with the message "Add feature X", replacing `X` with your corresponding letter.

![](/images/02-feature_branches/3.png)

→ Continue to [Pull Requests](/sections/03-pull_requests.md)
