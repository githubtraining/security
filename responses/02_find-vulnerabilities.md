## Step 2: Finding Vulnerabilities

Now you can find a vulnerability with your newly enabled settings. These settings are now automatically looking for several things. This project has some existing dependencies, or links to other projects, which may have some insecure code. Code can be insecure because of many reasons, but usually, when insecure code is found, it's fixed in updates.

### Where do vulnerabilities come from?

These are dependencies in this repo's language, x. See examples of other dependencies in other languages that are supported in [here](https://cve.mitre.org/).
How can we know they're secure? It's not always easy, but GitHub is watching out.

### [About security vulnerabilities](https://help.github.com/articles/about-security-alerts-for-vulnerable-dependencies/)
A vulnerability is a problem in a project's code that could be exploited to damage the confidentiality, integrity, or availability of the project or other projects that use its code. Depending on the severity level and the way your project uses the dependency, vulnerabilities can cause a range of problems for your project or the people who use it. You can track and resolve vulnerabilities for certain types of dependencies in your GitHub repository.

### GitHub's security alerts for vulnerable dependencies
GitHub tracks public vulnerabilities in Ruby gems, NPM and Python packages on [MITRE's Common Vulnerabilities and Exposures (CVE) List.](https://cve.mitre.org/)

When GitHub receives a notification of a newly-announced vulnerability, we identify public repositories (and private repositories that have opted in to vulnerability detection) that use the affected version of the dependency. Then, we send security alerts to owners and people with admin access to affected repositories. You can also configure security alerts for additional people or teams working in organisation-owned repositories.

GitHub never publicly discloses identified vulnerabilities for any repository.

### :keyboard: Activity:

Follow the GitHub Flow to update the deprecated package **todo: specify which file** in the `package.json` file. Here's how:

1. Step Locate vulnerable dependency in the file
2. Fix the vulnerability by applying the latest patch to the dependency (this could be as easy as upgrading to a version of the dependency which has the fix as a patch or new version)
3. Mark the fix depending its severity


For a printable version of the steps in this course, check out the [Quick Reference Guide]({{ host }}/public/{{ course.slug }}.pdf).

<hr>
<h3 align="center">Once you open a pull request, I'll continue looking at your work there.</h3>

> _Sometimes I respond too fast for the page to update! If you perform an expected action and don't see a response from me, wait a few seconds and refresh the page for your next steps._
