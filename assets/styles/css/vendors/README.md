# Vendors

The objective of this folder is to contain all the CSS files from external libraries and frameworks, like *Normalize*, *Bootstrap*, *jQueryUI*, and so on. Putting those inside of the same folder is a good way to say “Hey, this is not from me, not my code, not my responsibility”.

If you have to override a section of any vendor, it is recommended to create another folder called `vendors-extensions/` in which you may have files named exactly after the vendors they overwrite. For instance, `vendors-extensions/bootstrap.css` is a file containing all CSS rules intended to re-declare some of Bootstrap’s default CSS. This approach purpose is to avoid editing the vendor files themselves, which is generally not a good idea.

Reference: [Sass Guidelines for Vendors folder](https://sass-guidelin.es/#vendors-folder)