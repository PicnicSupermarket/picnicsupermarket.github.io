Picnic Technologies Open Source Website
=========================

Showcasing our latest open-source projects.

Live at: [http://picnic.tech](http://picnic.tech)

## How to build locally
1. Make sure you have bundler installed, if not run `gem install bundler`
2. `> git clone git@github.com:PicnicSupermarket/picnicsupermarket.github.io.git`
3. Run `bundle install` to install all dependencies
4. `> cd picnicsupermarket.github.io`
5. `> jekyll serve`
6. View at `http://127.0.0.1:4000`

## How to add a new project
1. Create a new file in the `_posts` folder which follows the naming conventions.
2. The mandatory fields are: `layout`, `title`, `technology`, `image`, `desc`, `proj-url`, `proj-num`.
3. If this is a "Coming Soon" project, use the `coming-soon.png` image. Otherwise, drop a new file in the `images` folder and simply reference it by its name.
4. Regenerate the site using `jekyll build --future`.

## Built using
+ [GitHub Pages](https://pages.github.com/)
+ [Jekyll](https://jekyllrb.com/)
+ [Jekyll-grid theme](http://femmebot.github.io/jekyll-grid)
