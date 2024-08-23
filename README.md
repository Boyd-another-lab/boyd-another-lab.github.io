# developer-site

This site is automatically deployed to https://developer.kehe.com upon commits to the trunk branch called `main`.


### Adding a page

To add a page, follow these steps.

1. Create a new `.md` file with a name that describes the page.
2. If the page is part of a menu, add the menu information at the top of the page.  For example, if the addition is going in the Development Stack menu:

    ```
    ---
    parent: Development Stack
    ---
    ```

    The text that should go after `parent:` can be found by looking at the `index.md` within the folder for the menu the page is being added to.
