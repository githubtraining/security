## Finding vulnerable dependencies

Security vulnerabilities can cause a range of problems for your project or the people who use it.  A vulnerability could affect the confidentiality, integrity, or availability of a project.  Sometimes vulnerabilities aren't in the code you write, but in the code your project depends on. Staying up-to-date with the most recent versions is the best line of defense.

This repository has some existing dependencies which will need updating to stay secure.

### How can we identify dependencies and if they are vulnerable?

This repository is a Node.js project utilizing NPM. Because of that, the `package.json` defines this repository's dependencies.  For our time together, we'll be focusing on these JavaScript dependencies. Keep in mind that different programming languages may have different dependency files. You might work with a `Gemfile`, `Gemfile.lock`, `*.gemspec`, `requirements.txt`, or `pipfile.lock` file.

How can we know these dependencies are secure? It's not always easy, but GitHub is watching out.

### GitHub's security alerts for vulnerable dependencies
GitHub tracks public vulnerabilities in Ruby gems, NPM and Python packages.

GitHub receives a notifications of a newly-announced vulnerability. Then, we check for repositories that use the affected version of that dependency. Then, we send security alerts to a set of people within those affected repositories. The owners are the ones contacted by default. But, it's possible to configure specific teams or individuals to get these important notifications.

**GitHub never publicly discloses identified vulnerabilities for any repository.**

### :keyboard: Activity: Identify the suggested version update

Use GitHub's security alerts to identify a vulnerable NPM dependency. Here's how:

1. Click the **Insights** tab in your repository
1. On the left hand navigation bar, click **Dependencies**
1. Scroll down until you see a yellow bar highlighting the dependency named `debug`, and click on the right hand side of the yellow `debug` section
1. Take note of the suggested version
1. Comment in this issue with the suggested update version

For a printable version of the steps in this course, check out the [Quick Reference Guide]({{ host }}/public/{{ course.slug }}.pdf).

<hr>
<h3 align="center">Return to this issue for my next comment</h3>
