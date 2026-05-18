<h2 id="education" style="margin: 2px 0px 10px;"><i class="fa-solid fa-graduation-cap" style="color:#e74d3c; margin-right: 6px;"></i> Education</h2>

<div class="education">
<ol class="bibliography" style="list-style: none; padding-left: 0;">

{% for edu in site.data.education.education %}

<li>
  <div class="pub-row">
    {% if edu.logo %}
    <div class="col-sm-3 abbr" style="position: relative;padding-right: 0px;padding-left: 15px;">
      <img src="{{ edu.logo }}" style="width: 60px; height: auto;">
    </div>
    <div class="col-sm-9" style="position: relative;padding-right: 15px; padding-left: 20px;">
    {% else %}
    <div class="col-sm-12" style="position: relative;padding-right: 15px; padding-left: 15px;">
    {% endif %}
      <div style="display:flex; justify-content:space-between; align-items:baseline; gap: 12px;">
        <div class="title"><strong>{{ edu.name }}</strong></div>
        <div style="font-style: italic; white-space: nowrap;">{{ edu.date }}</div>
      </div>
      <div class="author">{{ edu.position }}</div>
    </div>
  </div>
</li>

<br>

{% endfor %}

</ol>
</div>
