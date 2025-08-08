# Pull Requests

Now that you've worked on your own feature, how do you share your code with your team? You make a **pull request**!

All students should follow these next steps.

## Create a pull request

1. Run `git push -u origin feature-X` to push the changes to a _remote_ branch, replacing `X` with your letter.
2. In your browser, navigate to the main repository page on GitHub.
3. Go to the **Pull requests** tab.
   ![](/images/03-pull_requests/1.png)
4. Click on the **New pull request** button.
   ![](/images/03-pull_requests/2.png)
5. Select **main** in the **base:** dropdown.
   ![](/images/03-pull_requests/3.png)
6. Select **feature-X** in the **compare:** dropdown, replacing `X` with your letter.
   ![](/images/03-pull_requests/4.png)
7. Add a title and description for your pull request. This is usually a brief summary of what you worked on. In this case, you can write something along the lines of "Completed feature X".
   ![](/images/03-pull_requests/5.png)
8. Click the **Create pull request** button.

## Review a pull request

You will be able to see all pull requests when you navigate to the **Pull requests** tab. The next step in the process is for someone to review the open pull requests.

![](/images/03-pull_requests/6.png)

### Student B

1. Navigate to the **Feature A** pull request.
2. When you review a pull request, you should leave comments, ask questions, or provide suggestions to the requester. Leave a comment like "Looks good to me!" on the pull request.
   ![](/images/03-pull_requests/7.png)
3. Approve the PR and merge it in by clicking the **Merge pull request** button.
   ![](/images/03-pull_requests/8.png)
4. Confirm that `feature-A` has been merged into `main` by navigating back to the repo's **Code** page. The `README` should now contain the text that Student A added.
   ![](/images/03-pull_requests/9.png)
5. What happens to the PR for `feature-B` and `feature-C`? If you see a message about conflicts, then you're on the right track!
   ![](/images/03-pull_requests/10.png)

→ Continue to [Merge Conflicts](/sections/04-merge_conflicts.md)
