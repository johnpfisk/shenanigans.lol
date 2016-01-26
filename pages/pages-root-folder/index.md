---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: "shen-bg-001.jpg"
widget1:
  title: "Pictures"
  url: '/pictures/'
  image: shen-man-001.png
  text: 'Shenanigans in Pictures'
widget2:
  title: "Videos"
  url: '/videos/'
  image: shen-man-002.png
  text: 'Shenanigans in Videos'
widget3:
  title: "Stories"
  url: '/stories/'
  image: shen-man-005.png
  text: 'Shenanigans in Stories'
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
#  text: Inform me about new updates and features ›
#  style: alert
#  permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
