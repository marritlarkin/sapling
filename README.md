# Siteleaf-custom-theme
This is a custom theme for Siteleaf. Currently this theme only accounts for a single page with limited content -- meant to serve as a landing page for your home on the internet.

## This is what it looks like
![alt text](screenshot.png)

## How to use it
### Siteleaf


  1. Fork this repository.
  2. Connect your Siteleaf site to your Github branch in Settings > Sync > Repo
  3. In Siteleaf `/settings`:
    - The Site Title will be used in the top left of the page.
    - Under social, add new social accounts and urls and they will show up in the footer of the site.
    - The site description setting is used for SEO things.
    - **Fonts**: Here you can add a link to Typekit, Typography.com, etc. (i.e `<link rel="stylesheet" type="text/css" href="https://cloud.typography.com/1234567/1234567/css/fonts.css" />`)
    - **Font Style**: This is a place for you to add custom CSS for your fonts. (i.e `.footer, .header p {font-family: "Gotham SSm A","Gotham SSm B"; font-weight: 700; font-style: normal;}`)
    - The rest of the content is managed via the page content.
  4. Create a page and make sure the Default Layout is selected in Advanced Options (this will be your homepage)
  5. Give it a title

#### Layout Notes:

  - The `content` of the page is what shows up in between the tiny lines in the middle of the page
  - The `header` field shows in the top right of the page
  - The `image` field holds the main site image. (It should be big in resolution but not file size. The placeholder is 1440 × 2000 pixels and 106kb.). We recommend [TinyPNG](https://tinypng.com/) for image crunching.

### Jekyll (Standalone HTML)

Jekyll requires Ruby to run.

Install dependencies with `bundle install`. `gem install bundler` may be necessary if `bundle` doesn't run for you.

### Development

Run `bundle exec jekyll serve` to compile and serve the site at [localhost:4000](http://localhost:4000).

If you only want to compile, run `bundle exec jekyll build` which will compile the static site into the `_site` folder.
