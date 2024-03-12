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


Lopez-Restrepo, S., Yarce Botero, A., Pinel Peláez, N., Quintero, O. L., Segers, A., Heemink, A. W., Data Assimilation as a Tool to Improve Chemical Transport Models Performance in Developing Countries, Environmental Sustainability: Preparing for Tomorrow 18, 99 (2021).

Lopez-Restrepo, S., Niño Ruis, E. D., Guzman Reyes, L. Yarce Botero, A., Pinel, N., Quintero, O. L., Segers, A., Heemink, A. W., An efficient ensemble Kalman Filter implementation via shrinkage covariance matrix estimation: exploiting prior knowledge,Computational Geosciences 25,985 (2021)

Hinestroza-Ramirez, J., Rengifo-Castro, J., Quintero, O., Yarce Botero, A.,Rendon-Perez, A, Non-Parametric and Robust Sensitivity Analysis of the Weather Research and Forecast (WRF) Model in the Tropical Andes Region.,Atmosphere,14(4), 686. (2023)

Hinestroza-Ramirez, J., Soto Barbosa,J.E, Yarce Botero, A., Suarez Higuita, D.A., Lopez Restrepo,S.,..., Quintero Montoya,O.,textbf Evaluation of the 3DVAR Operational Implementation of the Colombian Air Force for Aircraft Operations: A Case Study,Climate, 11(7), 153, (2023)

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
