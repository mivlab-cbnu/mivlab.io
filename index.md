---
---
## Machine Intelligence and Vision Laboratory (MIVLab) is committed to advancing both the **theoretical foundations** and practical applications of Machine Intelligence. We strive to deliver innovative solutions to **real-world challenges** in computer vision, healthcare, and beyond.


{% include section.html %}

## Notice
<!-- > ##### "**Science and everyday life cannot and should not be separated**." *— Rosalind Franklin* -->
Machine Intelligence and Vision Laboratory is looking for self-motivated Master and Ph.D students in Artificial Intelligence, Deep Learning, and Signal/Image Processing. (Currently, we are not accepting applications from international students.)

If you are interested in joining our team, please send your cv and statement of research interest to Prof. Chaehwa Yoo.  

{%
  include button.html
  link="contact"
  text="Contact us"
  icon="fa-solid fa-arrow-right"
  flip=true
%}

<!-- 
{% capture text %}


{%
  include button.html
  link="contact"
  text="Contact us"
  icon="fa-solid fa-arrow-right"
  flip=true
%}

{% endcapture %}

{%
  include feature.html
  image="images/home/mbzuai_2.jpg"
  link="publications"
  title="We bridge biology, multi-omics, AI, and data science"
  text=text
%} -->
<!-- 
{% capture text %}

We strongly believe in global access to open and reproducible science. Our tools, software, and resources are openly licensed and freely available for all to use and build upon. By fostering a culture of collaboration and transparency, we aim to accelerate scientific discovery and innovation that benefit all.

{%
  include button.html
  link="tools"
  text="Access our open-source tools"
  icon="fa-solid fa-arrow-right"
  flip=true
%}

{% endcapture %}

{%
  include feature.html
  image="images/home/open-infrastructure.jpeg"
  link="tools"
  title="Open science and reproducibility is our foundation"
  flip=true
  style="bare"
  text=text
%} -->
<!-- 
{% capture text %}

We are training and building a collaborative team of responsible researchers united by a shared vision. We are committed to create an inclusive environment and recognize that diversity — in people, ideas, and data — is essential for scientific creativity and discovery.

{%
  include button.html
  link="join"
  text="Be part of the team"
  icon="fa-solid fa-arrow-right"
  flip=true

%}

{% endcapture %} -->
<!-- 
{%
  include feature.html
  image="images/home/team.jpeg"
  link="join"
  title="Training the next generation of scientists"
  text=text
%} -->

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

<!-- 
{% capture col2 %}

<script type="module" src="https://cdn.jsdelivr.net/npm/bsky-embed/dist/bsky-embed.es.js" async></script>

  <bsky-embed
    username="khanlab.bio"
    mode=""
    limit="2"
    link-target="_blank"
    link-image="flase"
    load-more="true"
    disable-styles="false"
    custom-styles=".border-slate-300 { border-color: gray; }"
    date-format='{"type":"absolute","locale":"de-DE","options":{"weekday":"long","year":"numeric","month":"long","day":"numeric"}}'
  >
</bsky-embed>

{% endcapture %}

-->

{% include cols.html col1=col1 %}
