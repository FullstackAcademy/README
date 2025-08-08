# Merge Conflicts

Merge conflicts happen all the time, and knowing how to resolve them is one of the most important skills a software engineer should have.

In this scenario, `Feature A` has been approved and merged into the main branch. However, there is some code in `Feature A` that is incompatible with `Feature B`, which means that `Feature B` cannot be directly merged in. The developer who worked on `Feature B` will now have to account for those changes.

## Resolve the merge conflict

### Student B

1. Use `git branch` to confirm that you are still on the `feature-B` branch.
   ![](/images/04-merge_conflicts/1.png)
2. Run `git fetch origin main:main` to update your _local_ main branch with the changes on the _remote_ main branch.
3. Run `git merge main` to merge in the changes from the `main` branch into the current feature branch. You will run into a conflict! The error message will tell you which file needs to be fixed. In this example, you will need to fix `README.md`.
4. In `README.md`, you will see merge conflict syntax. Read more this syntax in [step 5 of GitHub's guide on merge conflicts](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-using-the-command-line#competing-line-change-merge-conflicts).
   ![](/images/04-merge_conflicts/2.png)
5. VS Code provides some helpful tooling to resolve merge conflicts. In this example, select **Accept Both Changes**, which will remove the merge conflict markers.
   ![](/images/04-merge_conflicts/3.png)
6. Save your changes to `README.md`.
7. In the terminal, run `git add README.md` and `git commit` _without a message_. An editor will appear with a default merge message. You can simply close it.
8. Run `git push` to update the remote feature branch with your fixes.
   ![](/images/04-merge_conflicts/4.png)

## Approve the updated PR

Once Student B has pushed their changes, their pull request will be automatically updated on GitHub!

Student A should follow the [steps in the previous section](/sections/03-pull_requests.md) to approve and merge Student B's pull request. If there is a Student C, then Student C should do this instead.

Congrats! You've just resolved your first merge conflict!

### Student C

If you are in a team of 3, then Student C should now repeat the steps that student B just did to resolve the merge conflict. Student A should review.

In summary:

1. Student B reviews and merges Student A's PR.
2. Student B fixes their own PR.
3. Student C reviews and merges Student B's PR.
4. Student C fixes their own PR.
5. Student A reviews and merges Student C's PR.

→ Continue to [Cleanup](/sections/05-cleanup.md)
