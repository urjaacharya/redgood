# `redgood`

`redgood` is a clean minimal javascript-less [hugo](https://gohugo.io/) theme for blogs. 

[**Demo**](https://redgood.netlify.app/)

## Installation

If the site is not a git repo, it is necessary to first run `git init`. Run the following command in the site root directory to add `redgood` as a submodule:

    git submodule add https://github.com/urjaacharya/redgood.git themes/redgood


## Getting started

1. Copy the contents of [`config.toml`](https://github.com/urjaacharya/redgood/blob/master/exampleSite/config.toml) in the [exampleSite](https://github.com/urjaacharya/redgood/tree/master/exampleSite) folder to a `config.toml` in the site root directory and update it as needed.
2. Copy all the contents from [`exampleSite/content`](https://github.com/urjaacharya/redgood/tree/master/exampleSite/content) to a `content` folder in the root directory. At the least, the folders `archive` and `pinnedPosts` need to be copied.
3. Run `hugo server` to begin developing.

## Adding contents

The contents of your site should be in `content` folder in the root directory. The folders is the `content` folder represent dfferent sections. The `archive` and `pinnedPosts` are special sections for displaying all posts and pinned posts, respectively.

Additional content directories for more content sections can be added as required. When adding new folders, also create a new  `_index.md` file inside each folder and add `title` and `weight` relevant for that section. Refer to [`_index.md`](https://github.com/urjaacharya/redgood/blob/master/exampleSite/content/post/_index.md) for an example.

## Contributing

For comments, questions, and bugs, please create an issue [here](https://github.com/urjaacharya/redgood/issues).




