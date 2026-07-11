---
---
## Machine Intelligence and Vision Laboratory (MIVLab) is committed to advancing both the **theoretical foundations** and practical applications of Machine Intelligence. We strive to deliver innovative solutions to **real-world challenges** in computer vision, healthcare, and beyond.


{% include section.html %}

## Notice
<!-- > ##### "**Science and everyday life cannot and should not be separated**." *— Rosalind Franklin* -->
MIVLab is looking for self-motivated Master/Ph.D students and Undergraduate interns in Artificial Intelligence, Deep Learning, and Signal/Image Processing. If you would like to join our lab, please contact Prof. Yoo with a curriculum vitae (CV), and (unofficial) transcript(s).

MIVLab에 관심있는 석사/박사과정 지원학생 및 학부 인턴은 간단한 이력서와 성적표를 첨부하여 유채화 교수에게 연락바랍니다.

{%
  include button.html
  link="contact"
  text="Contact us"
  icon="fa-solid fa-arrow-right"
  flip=true
%}


{% include section.html %}

{% capture col1 %}
## {% include icon.html icon="fa-solid fa-newspaper" %}Latest news

  {% assign sorted_news = site.data.news | sort: "date" | reverse %}
    {% for post in sorted_news limit:3 %}
    
  <div class="news-card">
    <div class="news-header">
        <span class="news-title">{{ post.title }}</span>
        <span class="news-date">{% include icon.html icon="fa-regular fa-calendar" %} {{ post.date | date: "%B %d, %Y" }} </span>
    </div>
    <div class="news-description">
        {{ post.description }} 
            {% if post.url %}
            <a href="{{ post.url }}" target="_blank">More...</a>
            {% endif %}
    </div>
  </div>

    {% endfor %}  
  
{%
  include button.html
  link="news"
  text="Read all news"
  icon="fa-solid fa-arrow-right"
  flip=true
  align=left

%}

{% endcapture %}


{% include cols.html col1=col1 %}
