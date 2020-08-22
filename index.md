---
#Cayman Blog Theme is a clean, responsive blogging theme for Jekyll, with social features. It is inspired by the Cayman Theme for Github Pages, which can be greatly used for single projects but not as blogging platform.
#
#This theme has instead all you need to start today blogging with Jekyll, and no effort: pages, posts, few social buttons. Try loading this on mobile too.
#
#Have a look at the Github page for more information.
#
#You find this descriptive text in the `index.md` file, so you can change it, or remove it completely, according to your needs.
#
# Here you can change the text shown in the Home page before the Latest Posts section.
#
# Edit cayman-blog's home layout in _layouts instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#


layout: home
---
<p>They link to the corresponding index pages!</p>
<ul>
{% for category in site.categories %}
<li><a href="{{ site.url }}/jekyll/category/{{ category | first | url_encode }}/index.html">{{ category | first }}</a></li>
{% endfor %}
</ul>
<p>These are the categories for all blog posts:</p>

