---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_unsplash_12.png
widget1:
    title: "Learn Sketch in 30 minutes"
    url: 'https://bohemiapps.teachable.com/courses/learn-sketch-in-30-minutes'
    text: 'Learn all the essentials to be able to start your design in Sketch. After half an hour you will know everything you need to jump right into the work.'
    video: '<iframe width="302" height="170" src="https://www.youtube.com/embed/zxwRj8jQNQY?rel=0&amp;controls=0&amp;showinfo=0" frameborder="0" allowfullscreen></iframe>'
widget2:
    title: "Learn how to create zombie game for iPhone"
    url: 'https://bohemiapps.teachable.com/courses/zombie-run-scary-maze-game-for-iphone'
    text: 'New course is here. Learn how to create scary zombie maze game for iPhone, publish it on App Store and profit from its sales.'
    video: '<iframe width="302" height="170" src="https://www.youtube.com/embed/-uu1KE61E9s?rel=0&amp;controls=0&amp;showinfo=0" frameborder="0" allowfullscreen></iframe>'
widget3:
  title: "Earn money on App Store"
  url: 'https://bohemiapps.teachable.com/courses/catch-the-snake-ios-game'
  text: 'iOS developers make huge amount of money, because iPhone is so popular. Want to grab your share? Take this course and I will teach you all you need to create your own iOS game and publish it on App Store, so you can make money from selling it.'
  video: '<iframe width="302" height="170" src="https://www.youtube.com/embed/J-rv1AGynaA?rel=0&amp;controls=0&amp;showinfo=0" frameborder="0" allowfullscreen></iframe>'
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
  url: http://skl.sh/2aEf41O
  text: Get all courses for just $0.99 ›
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
