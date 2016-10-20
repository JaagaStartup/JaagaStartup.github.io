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
  title: "Cowork"
  url: '/cowork/'
  image: cowork-small.png
  text: 'We are a not-for-profit community that shares skills, knowledge and networks to help each other build better ventures. Join us and work out of a beautiful, open coworking space on Richmond Road in Central Bangalore.'
widget2:
  title: "Host an Event"
  url: '/events/'
  image: events-small.png
  text: 'We regularly host events suitable for an entrepreneurial community and work with a number of creative individuals and organisations. Get in touch if you need a central location to host your audience!'
widget3:
  title: "Incubate"
  url: 'http://jaagasustain.in/incubate'
  image: sustain-small.png
  text: "We support entrepreneurs using technology to address environmental challenges with free coworking space and access to technology platforms, mentors and partners. Apply to solve real world problems around us."
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
  url: /cowork/
  text: Explore Coworking
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---