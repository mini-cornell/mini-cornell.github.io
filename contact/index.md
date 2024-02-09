---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

We have positions for posdtocs and research students. Please reach out if interested!

{%
  include button.html
  type="email"
  text="qiz4006@med.cornell.edu"
  link="qiz4006@med.cornell.edu"
%}
{%
  include button.html
  type="address"
  tooltip="Belfer Research Building"
  link="https://www.google.com/maps/place/Weill+Cornell+Medicine+-+Belfer+Research+Building/@40.7655886,-73.9561743,15z/data=!4m6!3m5!1s0x89c258c3d1890e85:0x9893f8c86968cc2!8m2!3d40.7655886!4d-73.9561743!16s%2Fg%2F11b6zmd_jn?entry=ttu"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="https://tech.cornell.edu/wp-content/uploads/2018/06/visit-us-thumbnail-360-1440x1166.jpg"
  caption="Cornell Tech Campus"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="https://news.weill.cornell.edu/sites/default/files/styles/news_story_featured_image/public/story_featured_images/01_30_14brblobbylg.jpg?itok=MyLQzjAB&c=d126ce4356d335b9c6969088db23e8d2"
  caption="Belfer Research Building"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
