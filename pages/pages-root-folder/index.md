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
  title: "Earn money on App Store"
  url: 'https://bohemiapps.teachable.com/courses/catch-the-snake-ios-game'
  text: 'iOS developers make huge amount of money, because iPhone is so popular. Want to grab your share? Take this course and I will teach you all you need to create your own iOS game and publish it on App Store, so you can make money from selling it.'
  video: '<iframe width="302" height="170" src="https://www.youtube.com/embed/J-rv1AGynaA?rel=0&amp;controls=0&amp;showinfo=0" frameborder="0" allowfullscreen></iframe>'
widget2:
  title: "Learn2Earn"
  url: 'https://youtu.be/5bl2itrW2RU'
  image: widget-learn2earn-302x170.png
  text: 'We are thrilled to present you our new initiative. We are in the process of setting up BOHEMIAPPS UNIVERSITY where we will offer ways of learning stuff that can be transformed to money for our students. Learn2Earn will bring only those articles and lectures that will have this very straight focus. Tell us what you think via Twitter <a href="http://twitter.com/bohemiapps">@bohemiapps</a>.'
widget3:
  title: "Xcode lectures"
  url: '#'
  image: widget-xcode-302x170.png
  #cannot use ' inside text or it crashes, have to use &apos;
  text: 'We are working on new Xcode series. Stay tuned for more info.'
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
  url: https://tinyletter.com/bohemiapps
  text: Inform me about Discounts & Hot Deals ›
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
