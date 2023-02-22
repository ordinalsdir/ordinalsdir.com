---
layout: page
title: SUBMIT COLLECTION (FREE)
permalink: /submit-collection/
---

{% if site.logo %}
<center>
<img src="/assets/img/{{ site.logo }}" class="site-logo" width="100" height="auto" style="border-radius: 50%"/>
</center>
{%- endif -%}
<br>
To submit a new collection you have to send an email to [ordinalsdir@gmail.com](ordinalsdir@gmail.com) with a json file with the following structure.

```json
{
  "name" : "Project name",
  "description" : "Project description",
  "firstInscriptionDate" : "YYYY-MM-dd HH:MM:SS UTC",
  "firstInscriptionNum" : 0,
  "lastInscriptionNum" : 0,
  "supply" : 100,
  "web" : "https://www.ordinalsdir.com",
  "twitter" : "https://twitter.com/project-name",
  "discord" : "https://t.co/project-name",
  "artifacts" :
  [{
    "artifactId": 0,
    "inscriptionId": "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx",
    "inscriptionNum": 42069
  }, {
    "artifactId": 1,
    "inscriptionId": "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx",
    "inscriptionNum": 42070
  }, {
    "artifactId": 2,
    "inscriptionId": "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx",
    "inscriptionNum": 42071
  }]
}
```

We also accept pull requests.
