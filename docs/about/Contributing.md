??? abstract "Document Control"

    !!! info "Page Owner: @crivetimihai"

    !!! info "User Story: Contributing Content and Feedback"
        **As a**: contributor

        **I want to**: contribute content

        **So that**: I can improve the documentation.

    !!! info "Status"
        - [X] Structure
        - [X] Draft
        - [ ] Reviewed by:
        - [ ] Ready

Style Guide
------------

- Please name your files using a short, descriptive name, in lowercase, separated by dashes. Example: `my-page-here.md` or `my-picture.png`. Do not include spaces in file names.
- Capture all screenshots in PNG format: `this-is-a-description-of-the-screenshot.png`.
- Place all images in the `img` directory and link using relative paths in markdown. Ex: `[My Image Description](./img/my-image-description.png)`.

For more information on supported markdown and notations, see the [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/extensions/admonition/) theme.

Creating pull requests
-----------------------

Example pull request for closing issues:

```
# Grab the latest changes
git pull

# Create a new branch
git checkout -b 123-my-defect

# Fix the defect ...
vim somefile
git add .
git commit -m 'Closes #123, fixed everything!!!'

# Check for conflicts
git fetch upstream
git branch --set-upstream-to=upstream/master
git rebase

# Push to origin
git push origin 123-my-defect
```

See: [Linking a pull request to an issue](https://help.github.com/en/github/managing-your-work-on-github/linking-a-pull-request-to-an-issue)
