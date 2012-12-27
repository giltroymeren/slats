slats
=========

A basic theme for [tumblr](http://tumblr.com) by [Troy Meren](http://troymeren.github.com/)

Installation
------------
1. Open your blog, i.e. go to `http://your-tumblr-url.tumblr.com`
2. Click *Customize*
3. On the left panel click the **Edit HTML** button.
4. Just paste the Simpleton code to the text editor that will appear.
5. Save 
6. Customize the theme with the different options available

Documentation
-------------
### Overview
- Supports all nine kinds of tumblr posts
  1. Text
  2. Chat
  3. Link
  4. Quote
  5. Ask
  6. Photo
  7. Photoset
  8. Audio
  9. Video
- Header contains:
  - blog title
  - links (can be customized but must change the `#blog-links` `ul` in the actual theme)
- Sidebar contains:
  - a 128px by 128px photo intended for the blog
  - blog description (can contain HTML)
  - search form
- Footer contains:
  - title of blog followed by a generic copyright format
  - this theme's information
  - credit to tumblr

### Third Party CSS Hacks
- [Clearfix Hack](http://nicolasgallagher.com/micro-clearfix-hack/) by Nicholas Gallagher
- [CSS Sticky Footer](http://www.cssstickyfooter.com/)
- [Meyer Reset](http://meyerweb.com/eric/tools/css/reset/) by Eric Meyer
- `normalize.css` from the [Bootstrap](http://twitter.github.com/bootstrap/) package

### Customization Defaults
- Colors
  - ButtonA (button normal background color): #555
  - ButtonB (button hover background color): #08C
  - Dark (text color and other subparts): #262626
  - Light: #F7F7F7
  - Main (accent): #0AF
  - Permalink: #CCC
  - Secondary (to accent): #08C
- Blog parts
  - Show permalink: True
  - Show sidebar: True
  - Show tags: True

### Known limitations/bugs:
1. The Permalink sidebar is still rendered in the **Ask** and **Submit** pages (MUST BE REMOVED)
2. Improve sidebar design
3. Clean up CSS code
4. Improve customization of colors
