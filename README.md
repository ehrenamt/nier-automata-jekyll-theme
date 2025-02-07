# Nier: Automata Jekyll Website Theme

![](https://img.shields.io/badge/Framework-Jekyll-3f1f1f)
![](https://img.shields.io/badge/v0.1-WIP-CDC8B0)

![Image of this website's homepage, demonstrating the layout and visual details.](/assets/images/home.png)

![Image of this website's 404 page, demonstrating the layout and visual details.](/assets/images/404.png)

This is a basic Jekyll theme built solely for aesthetic purposes and to replicate the NieR: Automata in-game menu.

It is currently a work-in-progress project. Although basic layouts have been implemented, the code needs to be refactored, cleaned, and it could use more features - in its current state it is only a basic blog site.

[Jekyll](https://jekyllrb.com/) is a static site generator built with the [Ruby](https://www.ruby-lang.org/en/) programming language. It is especially useful for creating static blogs or featuring products.

## Features

This theme supports

- CSS minification on build

There are no special features. This is a basic Jekyll theme built solely for aesthetic purposes and to replicate the NieR: Automata in-game menu.

There are certainly better and more accurate ways to replicate the main menu than vanilla HTML and CSS. Currently this is the stack it is written in. Additional Gems or CSS / JS libraries could potentially be added in updates for more advanced features and more game-accurate animations.

## Installation

- Clone this repository
- Run the following command
```
bundle install
```
- To view the site locally, run
```
bundle exec jekyll serve
```
- To build the site, run
```
bundle exec jekyll build
```

## Guide

Please follow the installation steps above. Your directory should look like this:

```
Name
----
assets
_data
_includes
_layouts
_posts
.gitignore
404.html
Gemfile
Gemfile.lock
index.html
README.md
_config.yml
```

Once the planned updates have been implemented, a detailed guide will be written.

## Inaccuracies

There are some key inaccuracies with this theme. The following is a non-exhaustive list of inaccuracies.

- Lack of icons in the horizontal top menu items
- Lack of arrow pointer on hover / selection of horizontal menu items
- Lack of style change to horizontal menu items when said menu item is selected
- Lack of left-to-right background colour change animation for column menus
- Lack of left-to-right typewriter effect for column menus
- Lack of arrow pointer on hover / selection of column menu items

Some of these may be fixed in the future.

## Updates

The following updates will eventually be implemented:

- Add pagination to ```blog``` route
- Fix system layout
- Add map / image layout
- Add a second post layout ( or layout similar to one of the numerous in-game layouts)
- Move code into correct files (currently it follows no stardard rules between layouts, includes, and .html templates.)
- Modify and reduce CSS based on best practices (removing nested styles)

There are no plans to update this beyond the listed improvements.

## License and Legal

This project is open source under the MIT License.

All rights to the NieR: Automata franchise and IP belong to their respective owners.

This project is not officially affiliated with Platinum Games or Square Enix in any capacity.

The author is not officially affiliated with Platinum Games or Square Enix in any capacity.
