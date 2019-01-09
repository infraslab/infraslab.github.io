---
layout: default
---

<h1>
    Welcome to <b>InfrasLab</b>
</h1>

<h2>
    <a href="{{site.windows-loc}}"
                   class="{% if page.url contains 'windows' %}menu{% endif %}">Windows</a>
</h2>
<ul>
    {% include listpages.html link='/windows/' %}
</ul>

<h2>
    <a href="{{site.unix-linux-loc}}" class="{% if page.url contains 'unix' %}menu{% endif %}">Unix / Linux</a>
</h2>
<ul>
    {% include listpages.html link='/unix-linux/' %}
</ul>

<h2>
    <a href="{{site.others-loc}}" class="{% if page.url contains 'others' %}menu{% endif %}">Others</a>
</h2>
<ul>
    {% include listpages.html link='/others/' %}
</ul>