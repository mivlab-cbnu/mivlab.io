---
title: Contact
nav:
  order: 6
  tooltip: 
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

The Machine Intelligence and Vision Labaratory (MIVLab) is located at the [School of Electrical Engineering](https://koamma.cbnu.ac.kr),  [Chungbuk National University](https://cbnu.ac.kr), Cheongju, Korea. 

- Email: [chaehway@chungbuk.ac.kr](mailto:chaehway@chungbuk.ac.kr) (PI), [mivlab.cbnu@gmail.com](mailto:mivlab.cbnu@gmail.com) (webmaster)
- Address: Rm 473, Bldg E8-3, Chungdae-ro 1, Seowon-gu, Cheongju, Korea 
- Telephone: +82 43 261 2421 

<div style="margin-top: 20px; margin-bottom: 10px;">
{%
  include button.html
  type="address"
  text = "Find us on map"
  tooltip =""
  link="https://maps.app.goo.gl/jS66jkLmrw7B5CYn8"
%}
</div>

{% include section.html %}

# {% include icon.html icon="fa-solid fa-handshake-angle" %}Join the Team

MIVLab is looking for self-motivated Master/Ph.D students and Undergraduate interns in Artificial Intelligence, Deep Learning, and Signal/Image Processing. If you would like to join our lab, please contact Prof. Yoo with a curriculum vitae (CV), and (unofficial) transcript(s).

MIVLab에 관심있는 석사/박사과정 지원학생 및 학부 인턴은 간단한 이력서와 성적표를 첨부하여 유채화 교수에게 연락 바랍니다.

- 장학금 관련 정보는 다음 링크를 참조:  [Scholarship](https://graduate.chungbuk.ac.kr/home/sub.php?menukey=10843) \\
If you are an international student, please check the link for financial support information: [Scholarship](https://graduate.chungbuk.ac.kr/eng/sub.php?menukey=10951)


{% capture col1 %}

{%
  include figure.html
  image="images/campus.jpg"
  caption="CBNU Campus"
%}

<style>
  img[src*="campus.jpg"], img[src*="eng.jpg"] {
    width: 100% !important;
    aspect-ratio: 16 / 9 !important; /* ★ 1:1 정사각형을 원하면 1 / 1 로 변경 가능 */
    object-fit: cover !important;     /* 비율 유지하며 넘치는 영역 크롭 */
    object-position: center;         /* 중앙 정렬 */
  }
</style>

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/eng.jpg"
  caption="Engineering Building"
%}

{% endcapture %}
{% include cols.html col1=col1 col2=col2 %}

