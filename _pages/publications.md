---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  <div class="publication-intro">
    <p>You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u></p>
  </div>
{% endif %}

{% include base_path %}

<div class="publications-container">
  {% assign current_year = site.time | date: "%Y" %}
  {% assign grouped_publications = site.publications | group_by_exp: "post", "post.date | date: '%Y'" | sort: "name" | reverse %}
  
  {% for year_group in grouped_publications %}
    <div class="publication-year-section">
      <h2 class="publication-year-header">{{ year_group.name }}</h2>
      <div class="publication-year-content">
        {% for post in year_group.items %}
          {% include archive-single.html %}
        {% endfor %}
      </div>
    </div>
  {% endfor %}
</div>

<div class="preprints-section">
  <h2 class="preprints-header">Preprints</h2>
  <div class="preprints-content">
    {% for post in site.preprints %}
      {% include archive-single.html %}
    {% endfor %}
  </div>
</div>

<script>
function copyCitation(citation) {
  navigator.clipboard.writeText(citation).then(function() {
    // Show a temporary success message
    const button = event.target.closest('.citation-btn');
    const originalText = button.querySelector('span').textContent;
    button.querySelector('span').textContent = 'Copied!';
    button.classList.add('copied');
    
    setTimeout(function() {
      button.querySelector('span').textContent = originalText;
      button.classList.remove('copied');
    }, 2000);
  }).catch(function(err) {
    console.error('Could not copy citation: ', err);
  });
}
</script>