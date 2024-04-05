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

1. Create a new branch in GitHub Desktop in the branches dropdown
2. Select new branch and give it the recipe name
3. If there are changes, bring them to the new branch by selecting the `Bring my Changes` field
4. Select `Switch Branch`
5. Open the project folder in your text editor, [VSCodium](https://vscodium.com/) is recommended.
6. If required, create a new folder under `content` for the recipe's category.
7. Right click on `TEMPLATE.md` and copy
8. Right click on the category folder for the recipe and paste.
9. Rename the file in lowercase with words separated by dashes
10. Fill in the content according to the template styles

## Committing Changes to GitHub


1. In the changes tab, select the files that will be committed to the branch (ie. the recipe)
2. Write a descriptive commit message if necessary.
3. Hit the commit button
4. Hit `Publish Branch` button (looks like a tab) to send the updated branch to GitHub
5. On the [recipes pull requests page](https://github.com/Shrinks99/recipes/pulls), make a new pull request (click button)
6. Select the new branch as the `compare` branch to merge into the main `base` branch
7. Note any relevant changes in the description.
8. Add Henry as a reviewer
9. Click the `Create Pull Request` button
10. After the pull request has been merged, delete the local copy of the branch in GitHub Desktop.
