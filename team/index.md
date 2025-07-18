---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

<!-- Current team members -->
{% include list.html data="members" component="portrait" filters="role: pi,alumni:false" %}
<br><br>

{% include list.html data="members" component="portrait" filters="role: postdoc,alumni:false" %}
<br><br>

{% include list.html data="members" component="portrait" filters="role: phd,alumni:false" %}
<br><br>

{% include list.html data="members" component="portrait" filters="role: undergrad,alumni:false" %}
<br><br>


<!-- Alumni section -->
## Alumni
{% include list.html data="members" component="portrait" filters="alumni:true" %}
