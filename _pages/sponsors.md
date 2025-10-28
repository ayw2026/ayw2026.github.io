---
layout: archive
title: "Sponsors"
permalink: /sponsors/
author_profile: true
---

We are deeply grateful for the generous support of our sponsors, whose contributions made this event possible and accessible to a wider audience.

## Academic Sponsors


<table cellspacing="0" cellpadding="0" class="sponsor-table">
  <thead>
    <tr>
      <th class="sr-only">Logo</th>
      <th class="sr-only">Description</th>
    </tr>
  </thead>
  <tbody>
    {% for sponsor in site.data.academic_sponsors %}
    <tr>
      <td>
        <a href="{{ sponsor.url }}" target="_blank" rel="noopener" class="visually-hidden"> {{ sponsor.name }} </a><br/>
        <a href="{{ sponsor.url }}" target="_blank" rel="noopener">
          <img src="{{ sponsor.logo | relative_url }}" alt="{{ sponsor.name }} logo" style="max-height:128px;" />
        </a>
      </td>
      <!--
      <td>
        <strong><a href="{{ sponsor.url }}" target="_blank" rel="noopener">{{ sponsor.name }}</a></strong><br/>
        {{ sponsor.description }}
      </td>
      -->
    </tr>
    {% endfor %}
  </tbody>
</table>

## Industry Sponsors

<table cellspacing="0" cellpadding="0" class="sponsor-table">
  <thead>
    <tr>
      <th class="sr-only">Logo</th>
      <th class="sr-only">Description</th>
    </tr>
  </thead>
  <tbody>
    {% for sponsor in site.data.industry_sponsors %}
    <tr>
      <td>
        <a href="{{ sponsor.url }}" target="_blank" rel="noopener" class="visually-hidden"> {{ sponsor.name }} </a><br/>
        <a href="{{ sponsor.url }}" target="_blank" rel="noopener">
          <img src="{{ sponsor.logo | relative_url }}" alt="{{ sponsor.name }} logo" style="max-height:128px;" />
        </a>
      </td>
      <!--
      <td>
        <strong><a href="{{ sponsor.url }}" target="_blank" rel="noopener">{{ sponsor.name }}</a></strong><br/>
        {{ sponsor.description }}
      </td>
      -->
    </tr>
    {% endfor %}
  </tbody>
</table>