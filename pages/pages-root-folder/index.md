---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage

  
widget1:
  title: "The KITAB blog"
  url: '/blog/'
  image: photo05.jpg
  text: 'Click here to see our latest research and insights into our data.'
widget2:
  title: "Our data"
  url: '/pilot/'
  image: textalignment.png
  text: 'Take a look at our data here using interactive visualisations.'
widget3:
  title: "Frequently Asked Questions"
  url: '/FAQs/'
  image: kitab2.png
  text: 'Do you have questions about our corpus or our data. Take a look at our FAQs!'
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
  url: http://kitab-corpus-metadata.azurewebsites.net
  text: Find a text - search the OpenITI metadata ›
  style: 
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
