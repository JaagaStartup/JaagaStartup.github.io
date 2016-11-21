---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage

image:
  title: logo.jpg

widget1:
  title: "Open"
  url: '/cowork/'
  image: roomtobreathe-small.png
  text: 'Coworking can be wonderful but we need room for our ideas to breathe and grow. Experience the most open coworking space in Bangalore. Being not-for-profit has its benefits!'
widget2:
  title: "Collaborative"
  url: '/cowork/'
  image: sharingskills-small.png
  text: 'Our community learns and grows together by sharing skills every week. We curate our well-rounded community so you can learn new skills and find solutions easily, collaboratively.'
widget3:
  title: "Green"
  url: '/cowork/'
  image: greenallaround-small.png
  text: "We believe we all have a responsibility to our surroundings. So we compost our food waste, use it to nourish our large terrace garden and enjoy the perks of a lovely environment for our lunch."
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
  url: /cowork/apply/
  text: Join Us!
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---