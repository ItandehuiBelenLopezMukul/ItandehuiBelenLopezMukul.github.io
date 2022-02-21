---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: Drama name.jpg
widget1:
  title: "Shadow Beauty"
  url: 'https://dramaname.social/'
  image: 3.jpg
  text: 'Una estudiante llamada Goo Ae Jin que es considerada fea bajo los estandares de belleza coreanos se ve obligada a lleva una doble vida, en la que aparenta ser una influencer llamada Genie.'
widget2:
  title: "Adult Trainee"
  url: 'https://dramaname.social/'
  text: 'Este drama nos relata tres historias que tiene como objetivo expresar las aventuras de amor en la adolesencia, dentro de estas encontramos a Jae Min, Yu Ra y Na Eun además este drama busca que la Generacion Z se sienta identificada y pueda revivir sus momentos en la adolescencia.'
  image: 1.jpg
widget3:
  title: "All of Us Are Dead"
  url: 'https://dramaname.social/'
  image: 2.jpg
  text: 'Un grupo de estudiantes se queda atrapado en la escuela luego de que un brote de un virus zombie es propagado, este grupo de jovenes debe buscar la manera de salir sin ser contagiados.'
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
