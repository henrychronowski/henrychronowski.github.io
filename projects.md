---
permalink: /projects/
---

<!--
   Copyright 2022 Henry R. Chronowski

   Built from Daniel Buckstein's template at https://dbuckstein.github.io/
   
   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
-->


[Home](../)

[Blog](/blog/)

[About](/about/)


# Projects

This is a catalogue of my projects and explorations in mostly chronological order. If you have any questions about a project feel free to reach out.

<ul>
  {% assign posts = site.categories['projects'] %}
  {% for post in posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>