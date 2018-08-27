# g-blocks-proto
Prototyping tool for Gutenberg blocks

## Get started
1. Checkout gh-pages branch
2. `gem update bundler`
3. `bundle install`
4. Run jekyll: `bundle exec jekyll serve -w`


## Compile the css
1. Run compass: `bundle exec compass compile`
2. Since there are `scss` files outside of the sass folder, these will not trigger a css compile on change. Take that into consideration when running `bundle exec compass watch`


## Block structure
- Each block should be placed on a separate folder inside `blocks`.
- Include the html file on `index.html`
- Include the sass file on `sass/style.scss`
- Common or theme styling styling should be placed on the `sass` folder
