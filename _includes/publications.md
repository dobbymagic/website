<h2 id="publications" style="margin: 2px 0px -15px;">Publications</h2>

<div class="publications">
<ol class="bibliography">

{% for link in site.data.publications.main %}

<li>
<div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
      <div class="title"><a href="{{ link.doi }}">{{ link.title }}</a></div>
      <div class="author">{{ link.authors }}</div>
      <div class="periodical"><em>{{ link.journal }}</em> {% if link.notes %} <strong> <i style="color:#e74d3c">{{ link.notes }}</i></strong>
      {% endif %}
      </div>
</div>
</li>

{% endfor %}

</ol>
</div>
