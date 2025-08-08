# Cleanup

You're almost done! The last step is to tidy up your local and remote environments. This is an important habit to start early, especially before you begin to work on more complicated projects.

All students should follow these next steps.

## Delete remote branch

1. Go to the repository's **Code** page on GitHub.
2. Go to the **Branches** page by clicking on the link or by appending `/branches` to the URL.
   ![](/images/05-cleanup/1.png)
3. You should see your feature branches listed with a status of "Merged".
4. Click the **Trash** icon to delete your remote feature branch.
   ![](/images/05-cleanup/2.png)
   ![](/images/05-cleanup/3.png)

> [!NOTE]
> Don't worry about making a mistake! Deleted branches can be restored.

## Delete local branch

1. In your VS Code terminal, run `git switch main` to return to the `main` branch.
2. Run `git pull` to fetch all of the newly updated code from the remote repository.
3. Run `git branch -d feature-X` to delete your local feature branch, replacing `X` with your letter.
   ![](/images/05-cleanup/4.png)

That's it! You're done!

→ Continue to [Recap](/sections/06-recap.md)
