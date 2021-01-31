---
layout: template1
title: About
comments: false
---

<div class="jumbotron">
    <p>{{ site.desc }}</p>
    <p><a class="btn btn-lg btn-primary" href="https://vickytei.github.io/VisMat-Metadata-Framework/" role="button">View {{ site.title }} Code on Github &raquo;</a></p>
</div>

# Description

The {{ site.title }} outlines the use of metadata types for Visual Materials.

# API

| Function                          | Returns |
| --------------------------------- | ------- |
| ```/api/brays.json```             | [Brays](https://github.com/uhlibraries-digital/brays) application data as JSON |
| ```/api/carpenters.json```        | [Carpenters](https://github.com/uhlibraries-digital/carpenters) application data as JSON |
| ```/api/elements.json```          | All metadata elements as JSON |
| ```/api/graph.jsonld```           | {{ site.title }} graph as JSON-LD |
