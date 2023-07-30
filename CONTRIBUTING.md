# Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

## Bug reports

When `reporting a bug <https://github.com/ibaris/factor-risk-modeling/issues>`\_ please use the `bug` template and include:

-   Your operating system name and version.
-   Any details about your local setup that might be helpful in troubleshooting.
-   Detailed steps to reproduce the bug.

## Documentation improvements

Factor Risk Modeling could always use more documentation, whether as part of the
official Factor Risk Modeling docs, in docstrings, or even on the web in blog posts,
articles, and such.

## Feature requests and feedback

The best way to send feedback is to file an issue at https://github.com/ibaris/factor-risk-modeling/issues.

If you are proposing a feature use the template `request-feature` and :

-   Explain in detail how it would work.
-   eep the scope as narrow as possible, to make it easier to implement.
-   Remember that this is a volunteer-driven project, and that code contributions are welcome :)

## Development

To set up `factor-risk-modeling` for local development:

1. Fork `factor-risk-modeling <https://github.com/ibaris/factor-risk-modeling>`\_
   (look for the "Fork" button).
2. Clone your fork locally::

    git clone git@github.com:YOURGITHUBNAME/factor-risk-modeling.git

3. Create a branch for local development::

    git checkout -b name-of-your-bugfix-or-feature

    Now you can make your changes locally.

4. When you're done making changes run all the checks and docs builder with `tox <https://tox.wiki/en/latest/install.html>`\_ one command::

    tox

5. Commit your changes and push your branch to GitHub::

    git add .
    git commit -m "Your detailed description of your changes."
    git push origin name-of-your-bugfix-or-feature

6. Submit a pull request through the GitHub website.

### Pull Request Guidelines

If you need some code review or feedback while you're developing the code just make the pull request.

For merging, you should:

1. Include passing tests (run `tox`).
2. Update documentation when there's new API, functionality etc.
3. Add a note to `../src/.info/CHANGELOG.md` about the changes.
4. Add yourself to `../src/.info/AUTHORS.md`.

### Tips

To run a subset of tests::

    tox -e envname -- pytest -k test_myfeature

To run all the test environments in _parallel_::

    tox -p auto
