# Futel.net

The `gh-pages` branch for Futel.net is a [Jekyll](http://jekyllrb.com) site hosted on [GitHub Pages](https://pages.github.com/). As such, much of the documentaiton there will be helpful towards managing this site, but in particular this one: [Using Jekyll as a static site generator with GitHub Pages](https://help.github.com/articles/using-jekyll-as-a-static-site-generator-with-github-pages/).

- Requirements
- Running the site locally and previewing changes
- Previewing changes
- Making commits

## Requirements

You'll need the latest version of Jekyll installed on your machine to build and test locally. Requirements can be found on [the Jekyll installation page](https://jekyllrb.com/docs/installation/), but for most people on Linux/Unix/macOS installation should boil down to running `gem install jekyll jekyll-redirect-from` or `gem install --user-install jekyll jekyll-redirect-from` from the terminal.


## Running the site locally and previewing changes

Documentation for the options running a Jekyll site locally can be found on the [Jekyll basic usage](https://jekyllrb.com/docs/usage/) page, but here is a quickstart guide for running this site locally and previewing your changes:

- Change into the root directory for this project in the terminal.
- Run `jekyll s --watch`
- Open `http://localhost:4000` in your browser to preview the site
- As you make changes the site should rebuild itself automatically.


## Making commits 

To make a change to the site

- Fork the repo: [https://github.com/kra/futel.net](https://github.com/kra/futel.net)
- Checkout the `gh-pages` branch
- Start Jekylll per the previous section to preview your changes in real-time and make your changes
- When you're done with your changes create the commit and push it to your forked repo on GitHub
- Go to the **Pull Requests** tab in your forked project click the **New pull request** button. Make sure that you're creating a pull request from your `gh-pages` branch and requesting to merge it into futel.net's `gh-pages` branch.
- GitHub should tell you if it's possible to auto-merge. When it's done click **Create pull request** to submit  your proposed changes.
- After review and approval your changes will be merged.