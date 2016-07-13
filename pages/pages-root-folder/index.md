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
  text: 'We are a curated entrepreneurial community who share skills, networks and knowledge within a well laid out coworking space in central Bangalore. Join us to collaborate and help each other build stronger ventures.'
widget2:
  title: "Host an Event"
  url: '/events/'
  image: events-small.png
  text: 'We love hosting interesting, creative organisations and events. We offer free space to meetups and other free events targeting the entrepreneurial ecosystem. Get in touch if you need a central location to host your audience!'
widget3:
  title: "Incubate"
  url: '/sustain/'
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

<div class="small-6 large-centered columns">
	<h3 id="coworking-pricing" align="center">Pick a membership that suits you</h3>
	<br>

	<table><tbody><tr><td><b>Gold Membership</b></td><td>Dedicated seating + locker for teams in a room</td><td>₹5000</td></tr><tr><td><b>Silver Membership</b></td><td>Flexible seating for a whole month</td><td>₹4000</td></tr><tr><td><b>Friend Membership</b></td><td>Flexible seating for 5 working days in a month and unlimited weekends</td><td>₹2000</td></tr><tr><td><b>Off-Peak Membership</b></td><td>Flexible seating for unlimited mornings/evenings (pre-11am, post 6pm) and unlimited weekends</td><td>₹2000</td></tr></tbody></table>

</div>

