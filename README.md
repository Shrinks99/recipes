# Wilkinson Graphics Corporation Foodstuff Archive Division

Family recipes, now on the World Wide Web!

## Required Packages

This site uses Hugo as well as [Yarn](https://classic.yarnpkg.com/lang/en/docs/install/#mac-stable) to manage dependencies.

In addition to that, you also need to have [Dart Sass](https://gohugo.io/hugo-pipes/transpile-sass-to-css/#installing-in-a-development-environment) installed using your package manager of choice.

For macOS, install Dart sass with `brew install sass/sass/sass`.  Install Yarn with `npm install --global yarn`.

## Building for Development

1. Download a copy of the project to your computer.
2. Open Terminal
3. Navigate to the project folder with `cd`, eg: `cd /Users/Robin/Documents/GitHub/shrinks99/recipes`.

> [!TIP]
> After typing `cd` (the command we want to run to change the working directory) into the terminal, drag the project folder into the terminal window to get the full path!

4. If this is the first time setting up this project, run `yarn` to download everything required.

5. If the project is already set up, use the `hugo server` command to start Hugo on your local machine.  Navigate to [http://localhost:1313/recipes](http://localhost:1313/recipes) and get started!

## Writing and Submitting a Recipe

1. Open the project folder in your text editor, [VSCodium](https://vscodium.com/) is recommended.
2. If required, create a new folder under `content` for the recipe's category.
3. Right click on `TEMPLATE.md` and copy
4. Right click on the category folder for the recipe and paste.
5. Rename the file in lowercase with words separated by dashes
6. Fill in the content according to the template styles