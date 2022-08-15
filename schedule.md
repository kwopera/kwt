<h3 id="schedule"><a href="{{ "/schedule.html" | absolute_url }}#schedule">SEASON 2022/2023</a></h3>  
More performances being added as they are announced officially

<ul class="schedule">
  {% for post in site.posts reversed %}
    <a href="{{ post.link }}">
      <li>
        <h4 class="what">{{ post.title }}</h4>
        <p class="when">{{ post.when }} &nbsp;</p>
        <p class="where"><em>{{ post.who }}</em><br/>
        {{ post.where }}</p>
      </li>
    </a>
  {% endfor %}
</ul>