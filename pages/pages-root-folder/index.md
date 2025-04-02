---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_unsplash_12.jpg
widget1:
  title: "Games Work"
  url: 'http://phoebemansfield.github.io/portfolio/games/'
  image: widget-1-302x182.jpg
  text: 'Most of my games work takes place using Unity and C#. I have also utilised C++ and SDL2 along with imgui and other such libraries.'
widget2:
  title: "Custom Hardware and Firmwares"
  url: 'http://phoebemansfield.github.io/portfolio/hardware-and-firmware/'
  text: 'I tend to make my own tools to optimise my workflow, these can be hand wired or printed pcbs and custom programming using C or Python.'
  video: '<a href="#" data-reveal-id="videoModal"><img src="http://phlow.github.io/feeling-responsive/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "General Applications"
  url: 'http://phoebemansfield.github.io/portfolio/apps'
  image: widget-github-303x182.jpg
  text: 'I have built tools using Java and Kotlin dsl for Gradle or Unity C# for a variety of purposes, including google api automatition for administration purposes.'
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
  url: /portfolio/main
  text: Check out my most recent projects here.
  style: alert
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
