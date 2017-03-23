# Fungeoneering!
## Powered by [Jekyll](https://github.com/jekyll/jekyll)

## Quick Start

### Publishing posts

Posts live inside of `_posts/{CATEGORY_NAME}/`. To create a new post, add a new file to your desired category using the name structure of `YYYY-MM-DD-Post-Name.md`, then inside the post add the folder name as a category in the post's meta-data.

## Local Development

1. Install Jekyll and plug-ins in one fell swoop. `gem install github-pages` This mirrors the plug-ins used by GitHub Pages on your local machine including Jekyll, Sass, etc.
	a. If you run into an error (most like something like `jekyll-sitemap is missing!` then add that gem to your local environment by typing `gem install missing-gem-name-here`).
2. Clone down your fork.
3. Serve the site and watch for markup/sass changes `jekyll serve`.
4. View your website at `http://127.0.0.1:4000/`.
5. Commit any changes and push everything to the master branch of your GitHub user repository. GitHub Pages will then rebuild and serve your website.
