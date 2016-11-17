Let's add anything at all to our README. Open the file and add whatever text you'd like.
Now look at the remote repo on GitHub. Notice that the new text in your README is not there. Let's fix this by pushing our code up to GitHub.
If we git push right away, we still won't get the changes because we have not tracked and committed the changes. Let's do that: git add . and git commit -m "add content to README".
Now we can git push -u origin master. We only need to apply the -u flag (short for --set-upstream) the first time we use git push. It tells the current local branch to track itself against the master branch of origin, the remote repo we're pushing to. After you've set the upstream link with -u, you can use git push and git pull without specifying any arguments (such as a target branch or repo).
Confirm that your changes are now visible on GitHub, and you're done!
# code-along
