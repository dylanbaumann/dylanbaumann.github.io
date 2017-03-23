# Fungeoneering!

This is is powered by [Jekyll](https://github.com/jekyll/jekyll)

## Quick Start

All changes committed to this repository will automatically compile and be pushed to a live server thanks to [Github Pages](https://pages.github.com/). Feel free to click around inside of this repository and make any edits you'd like. If you don't have permission, then make a Pull Request and I'll take a look for you!

### Publishing new posts

Posts live inside of `_posts/{CATEGORY_NAME}/`. To create a new post, add a new file to your desired category using the name structure of `YYYY-MM-DD-Post-Name.md`, then inside the post add the folder name as a category in the post's meta-data.

For example, if you wanted to make a new "update", add a new file to `_posts/posts/` named `2017-03-21-New-Update.md` then add the following meta-information at the top of the post before beginning to write markdown:

![Category Example](http://i.imgur.com/mAsWDVu.png "Category Example")

## Local Development

1. Install Jekyll and plug-ins in one fell swoop. `gem install github-pages` This mirrors the plug-ins used by GitHub Pages on your local machine including Jekyll, Sass, etc.
	a. If you run into an error (most like something like `jekyll-sitemap is missing!` then add that gem to your local environment by typing `gem install missing-gem-name-here`).
2. Clone down your fork.
3. Serve the site and watch for markup/sass changes `jekyll serve`.
4. View your website at `http://127.0.0.1:4000/`.
5. Commit any changes and push everything to the master branch of your GitHub user repository. GitHub Pages will then rebuild and serve your website.
