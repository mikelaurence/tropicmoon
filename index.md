---
layout: default
title: "Home"
photos:
  - 2022-1-8 dark tentacle sphere.jpeg
  - 2022-1-11 a hill.jpeg
  - 2021-1-25 red mushroom field.jpeg
  - 2022-1-17 beam him up sprite.jpeg
  - 2020-4-4 tia in red.jpeg
  - 2018-12-16 messy-bodega-redshift.jpeg
  - 2020-3-3 laying on grid B.jpeg
---

# Tropic Moon

<div class="photos">
    {% for photo in page.photos %}
    <div class="photo">
        <img src="/assets/photos/{{ photo | url_decode }}">
    </div>
    {% endfor %}
</div>
