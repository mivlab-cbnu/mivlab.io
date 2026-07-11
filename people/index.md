---
title: People
nav:
  order: 2 
  # tooltip: Meet our team
---

# {% include icon.html icon="fa-solid fa-users" %}Meet Our Team

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}

{% include list.html data="members" component="portrait" filter="role != 'principal-investigator' and alumni != true" %}

### Undergraduate Intern

- Seunghyun Im 
- Sihyun Kim 
- Minwoo Yoon 
- Seonyo Lee 

<!-- #### <center>We strive to build an inclusive environment for research and recognize the value of diversity in the process of scientific creativity and discovery.</center> -->

<!-- {%
  include button.html
  icon="fa-solid fa-handshake-angle"
  text="Join the Team"
  link="contact"
  style="button"
%}  -->


{% include section.html %}

## Alumni

<!-- 
{% include list.html data="members" component="portrait-alumni" filter="alumni == true" style="small" %}
 -->

### Undergraduate Intern

- Seoyeon Kim (25.9-26.6)
- Yohan Jang (25.9-26.2)
- Dohee Kwon (25.3-26.2)

{% include section.html %}

