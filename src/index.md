---
layout: base.html
title: Classic Media Production
metaDescription:
  Classic Media Production provides exceptional printing services by pursuing business through innovation and creativity that exceed the expectation of our esteemed customers.
templateEngineOverride: njk
---

<section>
  <ul class="grid">
  {% for key, profile in profiles %}
    <li class="grid__item">
      <div class="grid__itemImgWrapper">
        <img src="/images/{{ key }}.png" alt="{{ profile.name }}" />
      </div>
        <h3>{{ profile.name }}</h3>
        <p>{{ profile.title }}</p>
    </li>
  {% endfor %}
</section>

<!-- "Space Grotesk", sans-serif -->