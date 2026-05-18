<h2 id="awards" style="margin: 2px 0px 10px;">🏆 Honors and Awards</h2>

<div class="awards">
<ol class="bibliography">

{% for award in site.data.awards.awards %}

<li>
  <div class="pub-row">
    <div class="col-sm-3 abbr" style="padding-left: 15px;">
      <span style="font-weight: bold;">{{ award.date }}</span>
    </div>
    <div class="col-sm-9" style="padding-left: 20px;">
      <div class="title">{{ award.name }}</div>
    </div>
  </div>
</li>

{% endfor %}

</ol>
</div>
