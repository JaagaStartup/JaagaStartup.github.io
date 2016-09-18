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

<div class="small-6 large-centered columns">
	<h3 id="coworking-pricing" align="center">Pick a membership that suits you</h3>
	<br>

<table>
    <tr>
        <td><b>Steady Jaagarnaut</b></td>
        <td>1 month membership - dedicated seating + locker</td>
        <td>₹5000</td>
    </tr>   
    <tr>
        <td><b>Flexible Jaagarnaut</b></td>
        <td>1 month membership - flexible seating</td>
        <td>₹4000</td>
    </tr>
    <tr>
        <td><b>Friendly Jaagarnaut</b></td>
        <td>1 month membership - flexible seating on all weekends + 5 full weekdays a month + pre-11am/post-6pm on all weekdays</td>
        <td>₹2000</td>
    </tr>

</table>

</div>
