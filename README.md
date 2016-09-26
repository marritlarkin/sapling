# Siteleaf-custom-theme
This is a custom theme for Siteleaf. Currently this theme only accounts for a single page with limited content -- meant to serve as a landing page for your home on the internet.

## How to use it
  - Fork this branch.
  - Connect your Siteleaf site to your Github branch in Settings > Sync > Repo
  - In /settings: 
    - The Site Title will be used in the top left of the page. 
    - Under social, add new social accounts and urls and they will show up in the footer of the site.
    - The site description setting is used for SEO things.
    - Fonts. Here you can add a link to Typekit, Typography.com, etc. (i.e `<link rel="stylesheet" type="text/css" href="https://cloud.typography.com/1234567/1234567/css/fonts.css" />`)
    - Font Style. This is a place for you to add custom css for your fonts. (i.e `.footer, .header p{font-family: "Gotham SSm A","Gotham SSm B";font-weight: 700;font-style: normal;}`)
    - The rest of the content is managed via the page content.
  - Create a page and make sure the Default Layout is selected in Advanced Options (this will be your homepage)
  - Give it a title
  - The `content` of the page is what shows up in between the tiny lines in the middle of the page
  - The `header` field shows in the top right of the page 
  - The `image` field holds the main site image. (It should be big in resolution but not size. The placeholder is 1440 × 2000 pixels and 106kb.)