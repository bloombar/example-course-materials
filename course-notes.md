---
title: Course Notes
permalink: /course-notes/
---

This page automatically shows a list of all the presentations stored in the `slides` directory. You can edit the file named `course-notes.md` to change this intro paragraph.

{% assign featured_categories = "course-notes" | split: ", "  %}

{% for cat in featured_categories %}<!-- use site.page-categories instead for all categories defined in config -->

<ul>
  {% for page in site.pages %}
    {% for pc in page.categories %}
    
      {% if pc == cat and page.name != "index.md" %}
      
        {% if page.path contains "index.md" %}
          <!-- ignore landing pages -->
        {% else %}

        <li><a href="{{ page.url | prepend:site.baseurl  }}">{{ page.title }}</a></li>
        {% endif %}

      {% endif %}   <!-- cat-match-p -->

    {% endfor %}  <!-- page-category -->

{% endfor %} <!-- page -->

</ul>

{% endfor %} <!-- cat -->
