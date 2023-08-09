---
layout: post
title: Kontakt
---

### Kontakt z nami

Lista linków do tweetera dla poszczegółnych osób w pętli zaczytania z pliku _data/people.csv

<ul>
{% for person in site.data.people %}
  <li>
    <a href="https://twitter.com/{{ person.twitter }}">
      {{ person.name }}
    </a>
  </li>
{% endfor %}
</ul>