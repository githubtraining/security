#### 1
- 🤖 Opens issue
    - Welcome! What are "secure repositories"? Glad you asked! Definition etc.
    - Post of examples going wrong
    - What are dependencies?
    - This course will...
    - When you are working with an existing project, there are some important steps to check its security.
    - Activity: Enable security settings.
    - Close this issue when you're ready.
- 👤Enable settings, Closes issues

#### 2
- 🤖 Opens Issue
    - There are several dependencies, one with a known vulnerability
    - Activity: branch and fix this
    - Comment: These are dependencies in this repo's language, `x`. See examples of other dependencies in other languages that are supported "here".
    - How can we know they're secure? It's not always easy, but GitHub is watching out. 👀
- 👤 Opens PR

#### 3
- 🤖 Watch PR to see if the dependency is updated properly
    - If yes, approve PR
    - If no, request changes and give more instructional help
- 👤 Merge PR

#### 4
- 🤖 Open PR
    - A `.gitignore` file is an important way to ignore files that might contain sensitive information.
    - Introduces `.gitignore` in PR
-  👤 Merge PR

#### 5
- 🤖 Open Issue
    - Now that we have a `.gitignore`, let's discuss what kind of files we should ignore.
    - One example is a `.env` file. It can contain sensitive information.
      - Possibly also include `.env.local` etc. `.config` possible too. Name can change but concept is the same for all projects.
      - Other generic files with authentication info, anything with passwords
      - Those things are better stored as environment variables, maybe point to OAuth as a GitHub App
    - Open a PR to change the name of the `.env` file, and add it to the `.gitignore`.
- 👤 Opens PR, changing `.env` title and, adding `.env` file to `.gitignore`.

#### 6
- 🤖 Watch PR to see if things are done correctly
    - If yes, approve PR
    - If no, request changes and give more instructional help
- 👤 Merge PR

#### 7
- 🤖 Open Issue
    - Great! Here are other important things.
    - This is what tokens are
    - What should happen if one is added?
    - What does GitHub do?
    - How will you know?
    - Yay you did it!
