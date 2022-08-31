---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# <i class="fas fa-envelope"></i>Contact

We are located on the 3rd floor of the Research Center of The Third Affiliated Hospital of Zhengzhou University. 

{%
  include link.html
  type="email"
  icon=""
  text="amczzu2006@163.com"
  tooltip=""
  link="amczzu2006@163.com "
  style="button"
%}
{%
  include link.html
  type="phone"
  icon=""
  text="(0371) 66903984"
  tooltip=""
  link="+86-0371-66903984"
  style="button"
%}
{%
  include link.html
  type="address"
  icon=""
  text="AMap"
  tooltip="Our location on AMap for easy navigation"
  link="https://www.amap.com/place/B0FFL70G6U"
  style="button"
%}
{:.center}

{% include section.html %}

### <i class="fas fa-mail-bulk"></i>Mailing Address

7 Kangfu Front St.,
Erqi District, Zhengzhou City, Henan Province,
China
{:.center}

{% capture col1 %}
{%
  include figure.html
  image="images/photo.jpg"
  caption="The Third Affiliated Hospital of Zhengzhou University"
%}
{% endcapture %}
{% capture col2 %}
{%
  include figure.html
  image="images/photo.jpg"
  caption="Wang Research Center"
%}
{% endcapture %}
{% include two-col.html col1=col1 col2=col2 %}
