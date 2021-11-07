# Twenty Fifteen

[1]: https://github.com/dmulholl/ivy
[2]: https://wordpress.org/themes/twentyfifteen/
[3]: http://www.dmulholl.com/demos/twentyfifteen/
[4]: https://github.com/dmulholl/holly

A blog-style, mobile-friendly theme for [Ivy][1] based on the classic [WordPress theme][2] of the same name.

* [Demo][3]

This theme is designed to be used with the [Holly][4] blog-engine plugin.
It will display the following attributes from the site's `config.py` file in the site header:

* `title`
* `tagline`

If a node has an `intro` attribute, this will be used as the snippet shown on index pages;
otherwise a snippet of text from the node's first paragraph will be used.

If a node has an `image` attribute containing the name of an image file stored in an `@root/images/` directory, this will be used as the node's featured image.

This theme supports the following includes:

* `menu`

    This file will be used to construct the theme's main menu. It should contain
    a list of links, optionally with nested sub-lists.

* `footer`

    This file should contain text or links to be displayed in the site's footer.

* `sidebar`

    This file can contain a series of H3 headings followed by paragraphs or lists of links.
    Its content is displayed below the site menu.

* `head`

    If a `head.html` file is present in the includes folder its content will be
    included at the end of each page's `<head>` section. This file can be used
    to add custom CSS or JavaScript to a site without directly editing the
    theme's template files.

* `foot`

    If a `foot.html` file is present in the includes folder its content will
    be included at the end of each page's `<body>` section. This file can be
    used to add custom JavaScript to a site without directly editing the
    theme's template files.
