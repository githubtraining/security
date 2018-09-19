## Step 3: Taking advantage of the .gitignore file for security

From time to time, there are files you don't want Git to check in to GitHub. There are a few ways to tell Git which files to ignore.
In this pull request, I'm adding a `.gitignore` file.

### Ignoring files

If you create a file in your repository named `.gitignore`, Git uses it to determine which files and directories to ignore, before you make a commit. This is one option where you can safely ignore any sensitive data that is stored in any `configuration` or `env` files, adhering to security best practices.

A `.gitignore` file should be committed into your repository, in order to share the ignore rules with any other users that clone the repository.

### :keyboard: Activity: Adding an .env file and updating the .gitignore file

1. Add an .env file to the root of the project.
2. Edit the .env file to store your user email for the purpose of this exercise. In reality, you will store sensitive data such as security tokens and user credentials required to support the run time of the awesome application you will be publishing.
3. Edit the `.gitignore` file at the root of the project to include the newly created `.env` file. This will ensure that the file will not be tracked and prevents from accidental commits.
4. Go ahead and merge the changes you have just completed.

For a printable version of the steps in this course, check out the [Quick Reference Guide]({{ host }}/public/{{ course.slug }}.pdf).

<hr>
<h3 align="center">Return to this issue for my next comment</h3>

> _Sometimes I respond too fast for the page to update! If you perform an expected action and don't see a response from me, wait a few seconds and refresh the page for your next steps._
