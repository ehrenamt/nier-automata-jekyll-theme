# Nier: Automata Jekyll Theme

![Image of this website's homepage, demonstrating the layout and visual details.](/assets/images/home.png)

> [!NOTE]
> Currently does not work on mobile. Mobile functionality is in development.

This is a basic Jekyll theme built solely for aesthetic purposes and to replicate the NieR: Automata in-game menu.

[Jekyll](https://jekyllrb.com/) is a static site generator built with the [Ruby](https://www.ruby-lang.org/en/) programming language. It is especially useful for creating static blogs or featuring products.

## Features

```config.yml``` is set up for pagination at ```/blog```. We're working on a mobile-friendly layout, but since the original game is meant for desktops, wide screens are the main focus.

There are certainly better and more accurate ways to replicate the main menu. Additional Gems or CSS / JS libraries could potentially be added in updates for more advanced features and more game-accurate animations.

## Installation

- Clone this repository

```
git clone https://github.com/ehrenamt/nier-automata-jekyll-theme
```

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
blog
_data
_includes
_layouts
_pages
_posts
_sass
.gitignore
404.md
Gemfile
Gemfile.lock
index.md
README.md
_config.yml
```

Once the planned updates have been implemented, a detailed guide will be written.

## Updates

The following updates will eventually be implemented:

- Improve code structure and fix semantic HTML
- Modify and reduce CSS based on best practices (removing nested styles)

There are no plans to update this beyond the listed improvements. There are many noticeable inaccuracies when compared to the actual in-game menu, but I am not aimed for a perfect 1:1 replica, but rather something as close as possible with minimal JS.

## License and Legal

This project is open source under the MIT License.

All rights to the NieR: Automata franchise and IP belong to their respective owners.

This project is not officially affiliated with Platinum Games or Square Enix in any capacity.

The author is not officially affiliated with Platinum Games or Square Enix in any capacity.
