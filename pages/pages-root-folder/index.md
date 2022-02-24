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
  title: "Shadow Beauty"
  url: 'http://phlow.github.io/feeling-responsive/blog/'
  image: widget-1-302x182.jpg
  text: 'Una estudiante llamada Goo Ae Jin es consideradad fea bajo los estandares de belleza coreanos, por lo tanto, se ve obligada a llevar una doble vida en la que aparenta ser una influencer llamada Genie'
widget2:
  title: "Adult Trainee"
  url: 'http://phlow.github.io/feeling-responsive/info/'
  image: start-video-feeling-responsive-302x182
  text: 'Este drama nos relata tres historias que tienen como objetivo expresar aventuras de amor en la adolescencia, dentro de estas historias encontramos a Jae Min, Yu Ra y Na Eun.'
  
widget3:
  title: "All of Us Are Dead"
  url: 'https://github.com/Phlow/feeling-responsive'
  image: widget-github-303x182.jpg
  text: 'Un grupo de estudiantes se queda atrapado en la escuela luego de que un brote de un virus zombie es propagado, este grupo de jovenes debe buscar la manera de salir sin ser contagiados'
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
  url: https://tinyletter.com/feeling-responsive
  text: Inform me about new updates and features ›
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
