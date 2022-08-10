---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
<!-- image: ../images/praneel.png  -->
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<!-- Publications -->
<!-- ====== -->

Journals
---
1. P. Acharya, K.D. Nguyen, H. La, D.K. Liu I.M. Chen, “Nonprehensile Manipulation: a Trajectory-Planning Perspective,”
IEEE/ASME Transactions on Mechatronics, 26 (1), 527-538, 2021. doi: [10.1109/TMECH.2020.3038591.](https://ieeexplore.ieee.org/document/9262053) 
2. E. Shata, K.D. Nguyen, P. Acharya, J. Doom, "A Series-Elastic Robot for Back-Pain Rehabilitation",
International Journal of Control, Automation, and Systems, 19 (2), 1054-1064, 2021. doi: [10.1007/s12555-019-0859-x](https://link.springer.com/article/10.1007/s12555-019-0859-x#citeas)

<!-- ![]({{page.image | relative_url}}) -->

Conference
---
1. Praneel Acharya, ElHussein Shata, Kim-Doang Nguyen, "Motion Planning for Nonprehensile Manipulation,"
IEEE International Conference on Electro/Information Technology, May 2019. doi: [10.1109/EIT.2019.8834164.](https://ieeexplore.ieee.org/abstract/document/8834164)
2. ElHussein Shata, Praneel Acharya, Kim-Doang Nguyen, "Brachiating Robot Analysis and Design,"
IEEE International Conference on Electro/Information Technology, May 2019. doi: [10.1109/EIT.2019.8833849](https://ieeexplore.ieee.org/document/8833849)
3. ElHussein Shata, Praneel Acharya, Marco Ciarcia, Kim-Doang Nguyen, "Optimization of a Chemical Reaction Using the Modified Quasilinearization Algorithm," IEEE International Conference on Electro/Information Technology, May 2019. doi: [10.1109/EIT.2019.8833909.](https://ieeexplore.ieee.org/abstract/document/8833909)



