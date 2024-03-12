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

Yarce Botero, A., Lopez-Restrepo, S., Pinel Peláez, N., Quintero, O. L., Segers, A., Heemink, A. W., Medellin Air Quality Initiative (MAUI)., Environmental Sustainability: Preparing for Tomorrow 18, 99 (2021).

Yarce Botero, A. et al.,Design and Implementation of a Low-Cost Air Quality Network for the Aburra Valley Surrounding Mountains., Pollutants 3.1 17, 549 (2023).

Yarce Botero, A., Lopez-Restrepo, S., Pinel Peláez, N., Quintero, O. L., Segers, A.,Heemink, A. W., Estimating NOx LOTOS-EUROS CTM Emission Parameters over the Northwest of South America through 4DEnVar TROPOMI NO2 Assimilation, Atmosphere, 12(12), 1633. (2021).

Yarce Botero, A., Quintero, O. L., Segers, A., Heemink, A. W., Estimating Wind and Emission Parameters in an atmospheric transport model, Eurosim (2023)(Submitted).

Yarce Botero, A., Santiago Lopez-Restrepo, Nicolas Pinel, O.L Quintero, Arjo Segers, and A.W. Heemink. (2017).Characterization and analysis of satellite and ground data available for the Aburrá Valley (Medellin Metropolitan Area) as inputs for air quality models, 3th CMAS South America Conference, Vitoria-Brazil .

Lopez-Restrepo, S., Yarce Botero, A., Pinel Peláez, N., Quintero, O. L., Segers, A., Heemink, A. W., Data Assimilation as a Tool to Improve Chemical Transport Models Performance in Developing Countries, Environmental Sustainability: Preparing for Tomorrow 18, 99 (2021).

Lopez-Restrepo, S., Yarce Botero, A., Pinel, N., Quintero, O. L., Segers, A., Heemink, A. W., A Knowledge-Aided Robust Ensemble Kalman Filter Algorithm for NonLinear and Non-Gaussian Large Systems,Frontiers Appl. Math. Stat.8 (2022)

Lopez-Restrepo, S., Yarce Botero, A., Pinel, N., Quintero, O. L., Segers, A.,Heemink, A. W.,Forecasting PM10 and PM2. 5 in the Aburrá Valley (Medellín, Colombia) via EnKF based data assimilation,Atmospheric Environment 232 (2020): 117507

Lopez-Restrepo, S., Yarce Botero, A., Pinel, N., Quintero, O. L., Segers, A., Heemink, A. W., Urban Air Quality Modeling Using Low-Cost Sensor Network and Data Assimilation in the Aburrá Valley, Colombia,Atmosphere 2021, 12(1),91 131

Lopez-Restrepo, S., Niño Ruis, E. D., Guzman Reyes, L. Yarce Botero, A., Pinel, N., Quintero, O. L., Segers, A., Heemink, A. W., An efficient ensemble Kalman Filter implementation via shrinkage covariance matrix estimation: exploiting prior knowledge,Computational Geosciences 25,985 (2021)

Hinestroza-Ramirez, J. E., Lopez-Restrepo, S., Yarce Botero, A., Segers, A., Rendon-Perez, A. M., Isaza-Cadavid, S., ... Quintero, O. L. ,Improving Air Pollution Modelling in Complex Terrain with a Coupled WRF–LOTOS–EUROS Approach: A Case Study in Aburrá Valley, Colombia,Atmosphere, 14(4), 738.(2023)

Hinestroza-Ramirez, J., Rengifo-Castro, J., Quintero, O., Yarce Botero, A.,Rendon-Perez, A, Non-Parametric and Robust Sensitivity Analysis of the Weather Research and Forecast (WRF) Model in the Tropical Andes Region.,Atmosphere,14(4), 686. (2023)

Hinestroza-Ramirez, J., Soto Barbosa,J.E, Yarce Botero, A., Suarez Higuita, D.A., Lopez Restrepo,S.,..., Quintero Montoya,O.,textbf Evaluation of the 3DVAR Operational Implementation of the Colombian Air Force for Aircraft Operations: A Case Study,Climate, 11(7), 153, (2023)

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
