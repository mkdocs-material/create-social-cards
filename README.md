# A Material for Mkdocs Social Cards Template

The purpose of the template in this repository is to give you a starting point
for setting up social cards for your projects, both standard ones and custom
cards for specific kinds of pages.

It reflects the results you get by going through the [social cards tutorials] 
in the documentation. 

[social cards tutorials]: https://squidfunk.github.io/mkdocs-material/tutorials#social-cards

## Requirements

To use all the features this template uses, you need the [Insiders
Edition] of Material for MkDocs but it should be easy enough to strip it down so
that it works with the public version.

[Insiders Edition]: https://squidfunk.github.io/mkdocs-material/insiders/

You will need to install the Cairo [image processing dependency] to use this
template.

[image processing dependency]: https://squidfunk.github.io/mkdocs-material/plugins/requirements/image-processing

## Using it

This is a [template repository], so you can create as many repositories from it 
as you like (unlike forks of which you can only have one at a time). These
repositories will contain only a single commit to start with, instead of the whole 
history of the template. Also, you can create a private repository from this template 
(while forks inherit the visibility settings from the original).

[template repository]: https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template

Simply hit the `Use this template` button above. You can set the specifics of your 
new repository from there.

## Project layout

The following shows the layout of the files in this template. Note that you can
configure Material for MkDocs to use a different layout, this is simply the
default.

```
docs/
    index.md                 # The documentation homepage.
    changelog.md             # changelog, used to demonstrate custom layout
    events/                  # subdirectory that contains event pages
        .meta.yml            # metadata for event pages
        firstevent.md        # an example event page
layouts/                     # directory for custom layouts and assets
    background_normal.png    # background image for 'normal' (not event)  pages
    release.yml              # custom layout for the changelog.md page
mkdocs.yml                   # The configuration file.
overrides/                   # Theme overrides directory
    .icons/                  # directory for custom icons
        logo-monochrome.svg  # SVG for logo used as icon
```

