## :tada: Welcome to Securing your workflows!

In this course, you'll learn how to build and host a secure repository in GitHub.  A secure repository is important for many reasons.
- Prevents exposing sensitive data
- Enforces secure development best practices
- Guards against unintended access rights permissions

In this course you will learn how to:

- Opt-in to vulnerability alerts for private repositories
  - _Note: These security settings are default for public repositories that are not forks._
- Detect and fix vulnerable dependencies when notified by a vulnerability alert
- Follow security best practices to protect sensitive data by using a `.gitignore` file

### New to GitHub?

For this course, you'll need to be comfortable with the GitHub Flow. If you need a refresher on the GitHub flow, check out the [the Introduction to GitHub course]({{ host}}/courses/introduction-to-github).

## Step 1: Your project on GitHub Pages

This project is centered around a memory game that will be deployed with GitHub Pages.

{% if private %}

### :keyboard: Activity: Enable vulnerability alerts & GitHub Pages


1. Click the [**Settings**]({{ repoUrl }}/settings) tab in your repository.
1. Scroll down until you see **Security & Analysis** in the navigation side bar.
1. Under **Security & Analysis**, click the check boxes to enable all the data services.
1. Scroll down to **GitHub Pages** and select `main` as a **Source**.

{% else %}

### :keyboard: Activity: Enable GitHub Pages


1. Click the [**Settings**]({{ repoUrl }}/settings) tab in your repository.
1. Scroll down to **GitHub Pages** and select `main` as a **Source**.

{% endif %}

For a printable version of the steps in this course, check out the [Quick Reference Guide]({{ host }}/public/{{ course.slug }}.pdf).

> Turning on GitHub Pages creates a deployment of your repository. I may take up to a minute to respond as I await the deployment.

<hr>
<h3 align="center">Return to this issue for my next comment.</h3>

> _Sometimes I respond too fast for the page to update! If you perform an expected action and don't see a response from me, wait a few seconds. Then refresh the page for your next steps._
