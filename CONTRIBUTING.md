# Contributing to The Art of Tech: Not Playing with a Full Tech community

## Contributing

When contributing to this repository, 

Please note we have a CODE_OF_CONDUCT.md, CODESTYLE.md and DEVSETUP.md within this repository.  Please review and follow them in all your interactions with the project.

Please create a new branch `<user>-<change>` with main as the target branch in whatever repository project you are working with. Make your changes in that branch.
   
## Projects
   
   Members with write and/or Admin access can create repository projects.  If you would like to create a project or resource for the organization, feel free to discuss this with the organization staff including @gbowne1.
   
Some things to think about:

1. Respect peoples' time.

2. Provide constructive feedback.

3. State exactly what needs to be improved.

4. Don't just pray or hope that the code works.

5. Be reasonable about `Temporary` code, it may or may not make it to final.

6. Big Picture your request. Remember, Code is not the line you write, but how the line integrates with and provides benefit to the application itself.

7. Review the code in chunks of 200-400 lines at the most.

8. Add comments on your pull request to help guide the reviewer  This is required.

9. Make it visual if possible. Add some screenshots if you believe that will help.

## Code Review Process

Your code must be reviewed by no less than 2 reviewers for code to be merged.  We will not be merging code that has not been reviewed.  If you feel like your code has no significant negative effect on the code base, we can discuss merging at that point.  Please state this in your description.

We will not merge any Pull Request without a 

## Issues and labels

Our Issues and Pull Requests require labeling for our bug and project tracking.  There is no good way for us to aggregate Issues or PR's without labels. So we will be requiring all Issues and Pull requests to have both a description, a good title and a com

Our bug tracker utilizes several labels to help organize and identify issues for both Issues AND Pull Requests. Here's what they represent and how we use them:

At the time this writing, our Labels are the defaults.  
   
   - Bug
      Use this tag for a PR that inlcudes fixes for a bug.
   - Documentation
      Use this tag for bugs, typos or errors in Doucmentation, or adding new Documentation
   - Enhancement
      Use this if the code you submitted in a Pull Request is an enhancement, or adds a feature or fixes for a enhancement/feature.
   - Good First Issue:
      This sends out to sites like goodfirstissue.com so use this tag to add 
   - Help Wanted
      Use this tag only to submit if you believe your code needs more help to be completed. 
   - Question
       Use this tag if your PR includes a question that you may have for other members. 
 
 We do not use the `invalid`, `wont-fix` or `duplicate` tags.

## Bug reports

A bug is a _demonstrable problem_ that is caused by the code in the repository.
Good bug reports are extremely helpful, so thanks!

Guidelines for bug reports:

As The Art of Tech: Not Playing with a Full Tech developers, we should strive for the best Bug Reports possible if not thorough.

 - Search the issues to see if the issue has been already added 
 - Try and describe how you discovered the issue.
 - Try and describe how you expected it to look and/or work.
 - Describe the issue as best as possible. We suggest no more than 200-250 words.
 - If there is more than one issue.  Feel free to submit issues for anything you find.
 - Describe where the bug happens (ie Browser, Console, Terminal, Compiler etc.)
 - If it's a browswer issue, add the version of your browser
 - Describe the platform (Mac, Linux, Windows)
 - If This issue affects a particular device, state Mobile or Desktop and any significant device information.
 - Include version numbers of Browser or any other related software/applications used
 - Let us know your IDE / editor and its' current version(s).
 - Let us know what tests you ran, hopefully with screenshots.
 - 

Our current Bug Report template leaves a little to be desired, but it is the default template. @@TODO

## Feature Requests

We welcome Feature requests. But take a moment to find out whether your idea
fits with the scope and aims of the project. It's up to *you* to make a strong
case to convince the project's developers of the merits of this feature. Please
provide as much detail and context as possible.

## Pull Requests (PR's)

We have very simple guidelines for Pull Requests

- Create a Pull Request, comparing your branch to 'main'.
- Assign a minimum or 2 reviewers
  Please note that we require a minimum of 2 reviews for Pull Requests to be merged.
- In the side panel, Assign yourself in the Asignees field.
- We require all PR's have labels. Choose at least one l(1) label that fits the type of change you are making.
- Most of our repository projects have Projects assosciated to them, so Choose the associated project in the Projects picker in the right side panel.
- Please provide a description in the top level panel.  We will NOT accept any Pull Requests without a description.
- Please provide a screenshot of the changes you made.
   
Good Pull Requests (PR's) patches, improvements and new features are a fantastic help. They should remain focused in scope and avoid containing unrelated
commits.

**Please ask first** before embarking on any **significant** pull request (e.g.
implementing features, refactoring code, porting to a different language),
otherwise you risk spending a lot of time working on something that the
project's developers might not want to merge into the project. For trivial
things, or things that don't require a lot of your time, you can go ahead and
make a PR.

Please adhere to the [coding guidelines](#code-guidelines) used throughout the
project (indentation, accurate comments, etc.) and any other requirements
(such as test coverage).

Adhering to the following process is the best way to get your work
included in the project:

1. [Fork](https://help.github.com/articles/fork-a-repo/) the project, clone your fork,
   and configure the remotes:

   ```bash
   # Clone your fork of the repo into the current directory
   git clone https://github.com/<your-username>/taotnpwaft.git
   # Navigate to the newly cloned directory
   cd taotnpwaft
   # Assign the original repo to a remote called "upstream"
   git remote add upstream https://github.com/twbs/bootstrap.git
   ```

2. If you cloned a while ago, get the latest changes from upstream:

   ```bash
   git checkout main
   git pull upstream main
   ```

3. Create a new topic branch (off the main project development branch) to
   contain your feature, change, or fix:

   ```bash
   git checkout -b <topic-branch-name>
   ```

4. Commit your changes in logical chunks. Please adhere to these [git commit
   message guidelines](https://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html)
   or your code is unlikely be merged into the main project. Use Git's
   [interactive rebase](https://help.github.com/articles/about-git-rebase/)
   feature to tidy up your commits before making them public.

5. Locally merge (or rebase) the upstream development branch into your topic branch:

   ```bash
   git pull [--rebase] upstream main
   ```

6. Push your topic branch up to your fork:

   ```bash
   git push origin <topic-branch-name>
   ```

7. [Open a Pull Request](https://help.github.com/articles/about-pull-requests/)
    with a clear title and description against the `main` branch.

**IMPORTANT**: By submitting a patch, you agree to allow the project owners to
license your work under the terms of the [GPL-V3](../LICENSE) (if it
includes code changes) and under the terms of the
[Creative Commons Attribution 3.0 Unported License](https://creativecommons.org/licenses/by/3.0/)
(if it includes documentation changes).


## Code guidelines

### HTML

[Adhere to the Code Guide.](https://codeguide.co/#html)

- Use tags and elements appropriate for an HTML5 doctype (e.g., self-closing tags).
- Use CDNs and HTTPS for third-party JS when possible. We don't use protocol-relative URLs in this case because they break when viewing the page locally via `file://`.
- Use [WAI-ARIA](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA) attributes in documentation examples to promote accessibility.

### CSS

[Adhere to the Code Guide.](https://codeguide.co/#css)

- When feasible, default color palettes should comply with [WCAG color contrast guidelines](https://www.w3.org/TR/WCAG20/#visual-audio-contrast).
- Except in rare cases, don't remove default `:focus` styles (via e.g. `outline: none;`) without providing alternative styles. See [this A11Y Project post](https://www.a11yproject.com/posts/2013-01-25-never-remove-css-outlines/) for more details.

### JS

- No semicolons (in client-side JS)
- 2 spaces (no tabs)
- strict mode
- "Attractive"

### Checking coding style

Run `npm run test` before committing to ensure your changes follow our coding standards.

Project maintainers and community aim to get issues resolved in timely fashion as per community support policy of this repo.

## Community Support Policy

Project maintainers will aim to respond within 3 business days to get a meaningful response for any new issues.

Don't hesitate to open a pull request, even if it's only a small change like a grammatical or typographical error in the documentation.
