---
layout: default
---

### **Airline API Overview**
The Airline API features functions that benefit a small airline. Within the documentation site, each function will be documented with an overview and additional function specifications.  

The following functions will be included within the API; the pending functions are noted with their release date. 

- Flight Information  
- Airport Information  
- Pilot Information  
- Airline Information  
- Plane Information and Scheduling **(Spring 2017)**
- Scheduling Flights  **(Spring 2017)**  

<div class="home">

  <h1 class="page-heading">Posts</h1>

  <ul class="post-list">
    {% for post in site.posts %}
      <li>
        <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>

        <h2>
          <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title | escape }}</a>
        </h2>
      </li>
    {% endfor %}
  </ul>

  <p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>
  <p class="post-date">Published: {{ 'now' | date: "%x %X" }} UTC</p>
</div>
