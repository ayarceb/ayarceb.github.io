---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}


Lopez-Restrepo, S., Niño Ruis, E. D., Guzman Reyes, L. Yarce Botero, A., Pinel, N., Quintero, O. L., Segers, A., Heemink, A. W., An efficient ensemble Kalman Filter implementation via shrinkage covariance matrix estimation: exploiting prior knowledge,Computational Geosciences 25,985 (2021)

Hinestroza-Ramirez, J., Rengifo-Castro, J., Quintero, O., Yarce Botero, A.,Rendon-Perez, A, Non-Parametric and Robust Sensitivity Analysis of the Weather Research and Forecast (WRF) Model in the Tropical Andes Region.,Atmosphere,14(4), 686. (2023)

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
