---
title: My page
permalink: /tweets
tweets:
  - https://twitter.com/dhh/status/1162426045405921282
  - https://twitter.com/rails/status/1205565185739673600
a_tweet: https://twitter.com/rubygems/status/518821243320287232
---

{% for tweet in page.tweets %}
{% twitter tweet %}
{% endfor %}

{% twitter page.a_tweet %}
