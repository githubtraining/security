## Taking advantage of the `.gitignore` file for security

From time to time, there are files you don't want Git to check in to GitHub. You may want to ignore files that contain sensitive credentials or other information which should not be pushed to your repository. There are a few ways to tell Git which files to ignore.

In this pull request, I'm adding a `.gitignore` file.

### Ignoring files

If you create a file in your repository named `.gitignore`, Git uses it to determine which files and directories to ignore when making a commit. This is one way to promote security best practices and keep files containing sensitive data, such as configuration or `env` files, out of your repositories.

Additionally, the `.gitignore` file can, and should, be committed into your repository.  By sharing this file and making it part of your code, it will also help other users that contribute to the repository to avoid committing sensitive data. There are many examples of `.gitignore` files available for you to use in your own projects in the [gitignore](https://github.com/github/gitignore) repository.

### :keyboard: Activity: Updating the .gitignore file

1. Within this pull request, go to **Files changed**.
1. Edit the `.gitignore` file at the root of the project to prevent an `.env` file from being added to the repository. This will ensure that the file will not be tracked and prevents from accidental commits.
    - _Note: Even after adding a file to the `.gitignore`, the previous commits that have edited that file still exist. Once sensitive information is committed, the most important thing is to change any tokens or passwords, and then contact GitHub Support for help correcting your history._

For a printable version of the steps in this course, check out the [Quick Reference Guide]({{ host }}/public/{{ course.slug }}.pdf).

<hr>
<h3 align="center">Return to this pull request for my next comment</h3>

> _Sometimes I respond too fast for the page to update! If you perform an expected action and don't see a response from me, wait a few seconds and refresh the page for your next steps._
