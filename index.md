## Welcome to My Page

This is my first page. I don't have much content for it yet, because I'm practicing.

### Moonshard

Moonshard is a good website.




### Support or Contact

Contact me on Discord : bit.ly/zindabuul

<ul> 
  {% for post in site.posts %}
  <li> 
    <a href = "{{ post.url }}" > {{ post.title }} </a>
  </li>
 {% endfor %}
 </ul>
