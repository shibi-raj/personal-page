---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
#
# header_unsplash_12.jpg
layout: frontpage
header:
  image_fullwidth: 
widget1:
  title: "About me"
  url: 'http://localhost:4000/portfolio/design/portfolio/'
  <!-- image: tree/gh-pages/images/new.jpg -->
  <!-- image: widget-1-302x182.jpg  -->
  text: "Passionate about data science.  Former physicist, but physics is still
  very much close to my heart.  Physics has been a guiding light and has given
  me the foundation for my critical thinking toolset."

widget2:

widget3:
  title: "Résumé"
  url: 'https://shibi-raj.github.io/portfolio/design/portfolio/' 
  text: 'Check out my résumé.'
  video: ''

# widget3:
#  title: ""
#  url:  ''
#  image: widget-github-303x182.jpg
#  text: '<em>Feeling Responsive</em> is free and licensed under a MIT License. Make it your own and start building. Grab the <a # # href="https://github.com/Phlow/feeling-responsive/tree/bare-bones-version">Bare-Bones-Version</a> for a fresh start or learn how # to use it with the <a href="https://github.com/Phlow/feeling-responsive/tree/gh-pages">education-version</a> with sample posts 
# and images. Then tell me via Twitter <a href="http://twitter.com/phlow">@phlow</a>.'


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
<!-- callforaction:
  url: https://tinyletter.com/feeling-responsive
  text: Inform me about new updates and features ›
  style: alert
permalink: /index.html
# -->
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
