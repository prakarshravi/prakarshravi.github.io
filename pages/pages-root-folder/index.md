---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: lon2.jpg
widget1:
  title: "About"
  url: '/about/'
  image: pp.png
  text: 'I enjoy enabling data driven decision making.'
widget2:
  title: "Portfolio"
  url: '/blog/'
  text: 'My complete works'
  image: portfolio.jpg
  # video: '<a href="#" data-reveal-id="videoModal"><img src="http://phlow.github.io/feeling-responsive/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "Design"
  url: '/design/'
  image: design.png
  text: 'For my views on design elements'

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
callforaction:
  url: https://www.linkedin.com/in/prakarshravi
  text: Let's connect. ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---