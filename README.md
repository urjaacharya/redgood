# `redgood`

`redgood` is a clean minimal javascript-less [hugo](https://gohugo.io/) theme for blogs.

## Installation
1. Add this theme as a git submodule in `themes` folder of your Hugo site:

    ```git submodule add https://github.com/urjaacharya/redgood.git themes/redgood```

    To run the above command, the folder of your hugo site must be a git repository. If it is not a git repository run `git init` to initialize the folder as git repository before running the above command.

## Getting started
1. Copy the contents of `config.toml` file of the theme to your site's `config.toml` file and update it as needed.
2. Copy the contents of `exampleSite/content` to your site's `content` folder.
3. Run `hugo server` in the terminal to view your site with the theme.

## Adding contents
The contents of your site should be in `contents` folder in the root directory. After following the forementioned steps, the `contents` directory should have `archive`, `pinnedPosts` and other additional folders. 
1. Remove all the folders except `archive` and `pinnedPosts`.
2. Create a folder inside the `contents` folder and then,
    - Create a new file `_index.md` inside the folder, and add `title` and `weight`. Refer to the `_index.md` file [here](https://github.com/urjaacharya/redgood/blob/master/exampleSite/content/post/_index.md).
    - Add your markdown contents to the folder.
3. If you want to categorize your posts then create separate folders for each category as mentioned in step 2 and add the markdown contents of belonging to each category in the specific folders. Make sure to add `_index.md` in each of these folders.

## Contributing
To contribute to the theme or report bugs, please create an issue [here](https://github.com/urjaacharya/redgood/issues).




