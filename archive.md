---
layout: page
title: Archive
---

## Events

{% for post in site.posts %}
  {% for tag in post.tags %}
    {% if tag == "events" %}
  * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ site.url }}{{ post.url }})
    {% break %}
    {% endif %}
  {% endfor %}
{% endfor %}

## Intelligence

{% for post in site.posts %}
  {% for tag in post.tags %}
    {% if tag == "intelligence" %}
  * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ site.url }}{{ post.url }})
    {% break %}
    {% endif %}
  {% endfor %}
{% endfor %}

## Research and Development

{% for post in site.posts %}
  {% for tag in post.tags %}
    {% if tag == "r&d" %}
  * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ site.url }}{{ post.url }})
    {% break %}
    {% endif %}
  {% endfor %}
{% endfor %}

## Hardware

{% for post in site.posts %}
  {% for tag in post.tags %}
    {% if tag == "hardware" %}
  * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ site.url }}{{ post.url }})
    {% break %}
    {% endif %}
  {% endfor %}
{% endfor %}

## Software

{% for post in site.posts %}
  {% for tag in post.tags %}
    {% if tag == "software" %}
  * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ site.url }}{{ post.url }})
    {% break %}
    {% endif %}
  {% endfor %}
{% endfor %}
