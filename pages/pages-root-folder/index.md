---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
skip_boilerplate: true
sidebar: left
header:
  title: Caroline Arden
  background-color: "#000535;"
widget1:
  title: "Bio"
  url: '/about/'
  image: caroline.jpeg
#  text: 'About Caroline Arden'
widget2:
  title: "Short Pieces"
  url: '/shorts/'
  image: header_unsplash_leaf_400x400.png
#  text: 'Short stories'
widget3:
  title: "The High Climber of Dark Water Bay"
  url: 'https://bookshop.org/p/books/the-high-climber-of-dark-water-bay-caroline-arden/9761800'
  image: highclimber.jpg
  #text: 'The High Climber of Dark Water Bay'

#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
#callforaction:
#  url: https://tinyletter.com/feeling-responsive
#  text: Do something important ›
#  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
