---
layout: default
title: page
tagline: A few more words default this theme
permalink: /header.html
---
<header class="page-header">
  <h1 class="project-name">{{ page-title }}</h1>
      <h2 class="project-tagline">{{ page-tagline }}</h2>
      {% if page.layout == 'home' and site.github.is_project_page %}
          <a href="{{ site.github.repository_url }}" class="btn">View on GitHub</a>
        {% if site.show_downloads %}
          <a href="{{ site.github.zip_url }}" class="btn">Download .zip</a>
          <a href="{{ site.github.tar_url }}" class="btn">Download .tar.gz</a>
        {% endif %}
      {% endif %}
</header><div>
</div>
