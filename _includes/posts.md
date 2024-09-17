<!-- <h3 id="publications" style="margin: 2px 0px -15px;">Posts</h3> -->
<!-- <div class="publications"> -->
<ol class="bibliography">
{% for link in site.data.posts.main %}
<li>
<!-- <div class="pub-row"> -->
  <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 0px;">
      <div class="title"><a href="{{ link.pdf }}">{{ link.title }}</a></div>
      <div class="tldr">{{ link.tldr }}</div>
  </div>
  <!-- </div> -->
</div>
</li>
{% endfor %}
</ol>
<!-- </div> -->
