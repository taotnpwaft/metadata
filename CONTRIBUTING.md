# Contributing to The Art of Tech: Not Playing with a Full Tech community

## Contributing

When contributing to this repository, please first discuss the change you wish to make via issue,
email, discussion or any other method with the owners of this repository before making a change.

Please note we have a CODE_OF_CONDUCT.md, CODESTYLE.md and DEVSETUP.md within this repository.  Please review and follow them in all your interactions with the project.

## Pull Request Process

1. Ensure any install or build dependencies are removed before the end of the layer when doing a
   build.

2. Update the CHANGELOG.nd with details of changes

3. Increase the version numbers in any examples files and the README.md to the new version that this
   Pull Request would represent. The versioning scheme we use is [SemVer](http://semver.org/).

4. You may merge the Pull Request in once you have the sign-off of at least one other developer, or if you
   do not have permission to do that, you may request the second reviewer to merge it for you.

Some things to think about:

1. Respect peoples' time.

2. Provide constructive feedback.

3. State exactly what needs to be improved.

4. Don't just pray or hope that the code works.

5. Be reasonable about `Temporary` code, it may or may not make it to final.

6. Big Picture your request. Remember, Code is not the line you write, but how the line integrates with and provides benefit to the application itself.

7. Review the code in chunks of 200-400 lines at the most.

8. Add comments on your pull request to help guide the reviewer

9. Make it visual if possible. Add some screenshots if you believe that will help.

## Code Review Process

We will be implementing a code review process to be described here.  Your code will have to pass CI/CD checks as well as reviews by a minimum of one maintainer/reviewer.

## Issues and labels

Our bug tracker utilizes several labels to help organize and identify issues. Here's what they represent and how we use them:

- `confirmed` - Issues that have been confirmed with a reduced test case and identify a bug.
- `docs` - Issues for improving or updating our documentation.
- `feature` - Issues asking for a new feature to be added, or an existing one to be extended or modified. New features require a minor version bump (e.g., `v3.0.0` to `v3.1.0`).
- `help wanted` - Issues we need or would love help from the community to resolve.
- `js` - Issues stemming from our compiled or source JavaScript files.
- `meta` - Issues with the project itself or our GitHub repository.

## Bug reports

A bug is a _demonstrable problem_ that is caused by the code in the repository.
Good bug reports are extremely helpful, so thanks!

Guidelines for bug reports:

## Feature requests

Feature requests are welcome. But take a moment to find out whether your idea
fits with the scope and aims of the project. It's up to *you* to make a strong
case to convince the project's developers of the merits of this feature. Please
provide as much detail and context as possible.

## Pull requests

Good pull requests—patches, improvements, new features—are a fantastic
help. They should remain focused in scope and avoid containing unrelated
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
