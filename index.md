---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
---



  <nav class="teal darken-1">
    <div class="nav-wrapper">
      <a href="#" class="brand-logo">Myszoskoczki</a>
      <ul id="nav-mobile" class="right hide-on-med-and-down">
        <li><a href="sass.html">Youtube</a></li>
        <li><a href="badges.html">Facebook</a></li>
        <li><a href="collapsible.html">Twitter</a></li>
      </ul>
    </div>
  </nav>


  <div class="collection">
    {% for page in site.pages %}
      {% if page.onTheList %}
        <a href="{{page.url}}" class="collection-item"><div class="card-panel brown lighten-3"><span class="white-text">{{ page.title }}</span></div></a>
      {% endif %}
    {% endfor %}

    <!--     <a href="jakkupic.html" class="collection-item"><div class="card-panel brown lighten-3"><span class="white-text">Czym są myszoskoczki?</span></div></a>
         <a href="#!" class="collection-item"><div class="card-panel brown lighten-3"><span class="white-text">Jak kupić?</span></div></a>
         <a href="#!" class="collection-item"><div class="card-panel brown lighten-3"><span class="white-text">Wybór klatki</span></div></a>
         <a href="#!" class="collection-item"><div class="card-panel brown lighten-3"><span class="white-text">Pielęgnacja</span></div></a>
       -->
 </div>
