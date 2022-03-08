---
title: Wordle Tweets
permalink: /tweets
layout: default
---

<div class="row">
{% for tweet in site.data.tweets %}
<div class="col-4 col-md-3 col-sm-1">
{% twitternocache tweet align=right width=350 %}
</div>
{% endfor %}
</div>
