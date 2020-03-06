# View this website

[Visit my page](https://emaiannone.github.io/)

# Modifying this website

You can not modify my site (!) but you can fork this repository and make your own one.

Each time you commit to a repository with a linked website GitHub Pages, automatically, will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown and HTML files and publish it in minutes.

## Serving the site on localhost

Some prerequisites:

- **Ruby** language, installed on your local machine
- **Gem** Ruby package manager, installed on your local machine
- **Bundle** gem on your local machine, installed by `gem install bundler`

1. Run `bundle install` (`bundle update` if you have already called it previously) so that all gems in the *Gemfile* will be installed, like **Jekyll**, needed to build your site your theme. In Gemfile, the gem will be installed in `usr/lib/ruby/gems`
2. Run `bundle exec jekyll serve` to build and serve the site at **http://localhost:4000** (with auto-regeneration when files are changed but without live-reload).

Make sure you have ruby/<version>/bin in your *PATH* variable, otherwise you are not able to easily call `bundle`.

## Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/emaiannone/emaiannone.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

When you want the site to be served in localhost the theme must be added as a gem into Gemfile. For remote serving this is not needed because GitHub Pages Jekyll ignores our Gemfile.

## More on GitHub Pages

Having trouble with Pages? Check out [documentation](https://help.github.com/categories/github-pages-basics/).
