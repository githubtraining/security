## Finding Vulnerabilities

Vulnerabilities can cause a range of problems for your project or the people who use it.  A vulnerability could affect the confidentiality, integrity, or availability of a project.  Especially when dealing with dependencies, updates usually improve or fix the code vulnerabilities.

This project has some existing dependencies which will need updating.

### Where do vulnerabilities come from?

These are dependencies linked in this repository's `package.json` and `package-lock.json` files. For our time together, we'll be focusing on these JavaScript dependencies, but many languages can have dependency files, like a `Gemfile`, `Gemfile.lock`, `*.gemspec`, `requirements.txt`, or `pipfile.lock` file.

How can we know these dependencies are secure? It's not always easy, but GitHub is watching out.

### GitHub's security alerts for vulnerable dependencies
GitHub tracks public vulnerabilities in Ruby gems, NPM and Python packages.

When GitHub receives a notification of a newly-announced vulnerability, we public repositories (and private repositories that have opted in to vulnerability detection) that use the affected version of the dependency. Then, we send security alerts to owners and people with admin access to affected repositories. Though the owners are the ones contacted by default, it's possible to configure specific teams or individuals to get these important notifications exclusively.

**GitHub never publicly discloses identified vulnerabilities for any repository.**

### :keyboard: Activity:

Follow the GitHub Flow to update the deprecated package `debug` in the `package.json` file. Here's how:

1. Click the **Insights** tab in your repository.
1. On the left hand navigation bar, click **Dependencies**.
1. Scroll down until you see a yellow bar highlighting the dependency named `debug`. Click the number on the right hand side of the yellow `debug` section. When a drop-down is enabled, take note of the suggested version.
1. Create a branch based off of `master`. If you aren't sure how to do this, try the [Introduction to GitHub course](https://lab.github.com/githubtraining/introduction-to-github) and then come back to give it another try.
1. Edit the `package.json` file.  Fix the vulnerability by applying the latest patch to the dependency that you took note of earlier. Commit your change.
1. Open a pull request with `base: master`.

For a printable version of the steps in this course, check out the [Quick Reference Guide]({{ host }}/public/{{ course.slug }}.pdf).

<hr>
<h3 align="center">Once you open a pull request, I'll continue looking at your work there.</h3>
