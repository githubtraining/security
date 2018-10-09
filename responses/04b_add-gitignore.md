## Taking advantage of the `.gitignore` file for security

From time to time, there are files you don't want Git to check in to GitHub. There are a few ways to tell Git which files to ignore.

In this pull request, I'm adding a `.gitignore` file.

### Ignoring files

If you create a file in your repository named `.gitignore`, Git uses it to determine which files and directories to ignore, before you make a commit. This is one option where you can safely ignore any sensitive data that is stored in any `configuration` or `env` files, adhering to security best practices.

A `.gitignore` file should be committed into your repository, in order to share the ignore rules with any other users that clone the repository. There are many examples of `.gitignore` files available for you to use in your own projects in the [gitignore](https://github.com/github/gitignore) repository.

### :keyboard: Activity: Adding an .env file and updating the .gitignore file

1. Within this pull request, go to **Files changed**.
1. Edit the `.gitignore` file at the root of the project to include a file named `.env`. This will ensure that the file will not be tracked and prevents from accidental commits.
    - _Note: Even after adding a file to the `.gitignore`, the previous commits that have edited that file still exist. Once sensitive information is committed, the most important thing is to change any tokens or passwords, and then contact GitHub Support for help correcting your history. In this case, no action is needed.

For a printable version of the steps in this course, check out the [Quick Reference Guide]({{ host }}/public/{{ course.slug }}.pdf).

<hr>
<h3 align="center">Return to this pull request for my next comment</h3>

> _Sometimes I respond too fast for the page to update! If you perform an expected action and don't see a response from me, wait a few seconds and refresh the page for your next steps._
