---
layout: default
---


<img src="./assets/figure/pipeline.png" alt="Drawing" style="width: 700px;" border="1"/>

# Fall 2016 Topic List

In reverse chronological order. A more detailed outline can be found [here](https://docs.google.com/spreadsheets/d/1msrQOV0zFjc5VUamFhRltz8GhS-uF010_rfaSwtTVXU/edit?usp=sharing). The GitHub repository corresponding to these lectures can be found <a target="_blank" class="page-link" href="https://github.com/2016-09-Middlebury-Data-Science/Topics">here</a>.


### 5. Text Data

<ul>
  {% for post in site.posts %}
    {% assign current_date = post.date | date: "%m %d" %}
    {% if "11 06" <= current_date and current_date <= "11 14" %}
    <li>
      {{ post.date | date: "%a %b %-d" }} -  
      <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>:
      {{ post.subtitle }}
    </li>
    {% endif %}
  {% endfor %}
</ul>  



### 4. Maps and Spatial Data

<ul>
  {% for post in site.posts %}
    {% assign current_date = post.date | date: "%m %d" %}
    {% if "10 23" <= current_date and current_date <= "11 05" %}
    <li>
      {{ post.date | date: "%a %b %-d" }} -  
      <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>:
      {{ post.subtitle }}
    </li>
    {% endif %}
  {% endfor %}
</ul>  




### 3. Dates and Times

<ul>
  {% for post in site.posts %}
    {% assign current_date = post.date | date: "%m %d" %}
    {% if "10 11" <= current_date and current_date <= "10 22" %}
    <li>
      {{ post.date | date: "%a %b %-d" }} -  
      <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>:
      {{ post.subtitle }}
    </li>
    {% endif %}
  {% endfor %}
</ul>  



### 2. Regression

<ul>
  {% for post in site.posts %}
    {% assign current_date = post.date | date: "%m %d" %}
    {% if "10 06" <= current_date and current_date <= "10 10" %}
    <li>
      {{ post.date | date: "%a %b %-d" }} -  
      <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>:
      {{ post.subtitle }}
    </li>
    {% endif %}
  {% endfor %}
</ul>  


### 1. Data Manipulation and Data Visualization

<ul>
  {% for post in site.posts %}
    {% assign current_date = post.date | date: "%m %d" %}
    {% if "09 11" <= current_date and current_date <= "10 06" %}
    <li>
      {{ post.date | date: "%a %b %-d" }} -  
      <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>:
      {{ post.subtitle }}
    </li>
    {% endif %}
  {% endfor %}
</ul>  
