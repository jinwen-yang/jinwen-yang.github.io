---
layout: archive
title: "Repositories"
permalink: /repositories/
author_profile: true
---

<!-- GitHub Repositories --> 

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.liquid repository=repo %}
  {% endfor %}
</div>
