## Finding vulnerable dependencies

Security vulnerabilities can cause a range of problems for your project or the people who use it.  A vulnerability could affect the confidentiality, integrity, or availability of a project.  Sometimes vulnerabilities don't live in the code you write, but in the libraries and software your project depends on. When dealing with vulnerable dependencies, staying up-to-date with the most recent versions is the best line of defense.

This repository has some existing dependencies which will need updating to stay secure.

### How can we identify dependencies and if they are vulnerable?

This repository's dependencies are defined in the `package.json` file because it's a Node.js project utilizing NPM. For our time together, we'll be focusing on these JavaScript dependencies, but many languages can have dependency files, like a `Gemfile`, `Gemfile.lock`, `*.gemspec`, `requirements.txt`, or `pipfile.lock` file.

How can we know these dependencies are secure? It's not always easy, but GitHub is watching out.

### GitHub's security alerts for vulnerable dependencies
GitHub tracks public vulnerabilities in Ruby gems, NPM and Python packages.

When GitHub receives a notification of a newly-announced vulnerability, we check against public repositories (and private repositories that have opted in to vulnerability detection) that use the affected version of the dependency. Then, we send security alerts to the owners of and people with admin access to the affected repositories. Though the owners are the ones contacted by default, it's possible to configure specific teams or individuals to get these important notifications exclusively.

**GitHub never publicly discloses identified vulnerabilities for any repository.**

### :keyboard: Activity:

Use GitHub's security alerts to identify a vulnerable NPM dependency. Here's how:

1. Click the **Insights** tab in your repository.
1. On the left hand navigation bar, click **Dependencies**.
1. Scroll down until you see a yellow bar highlighting the dependency named `debug`. Click the number on the right hand side of the yellow `debug` section. When a drop-down is enabled, take note of the suggested version.
1. Comment in this issue with the suggested update version.

For a printable version of the steps in this course, check out the [Quick Reference Guide]({{ host }}/public/{{ course.slug }}.pdf).

<hr>
<h3 align="center">Return to this issue for my next comment.</h3>
