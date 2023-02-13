---
layout: post
title:  "On the Edge of Oblivion"
date:   2023-02-07 04:25:13 +0000
firstInscriptionNum: 9978
lastInscriptionNum: 21623
image: https://ordinalsdir.com/assets/img/on-the-edge-of-oblivion.png
categories: sub1k
---
- Name : {{site.data.on-the-edge-of-oblivion.name}}
- Description : {{site.data.on-the-edge-of-oblivion.description}}
- First inscription date : {{site.data.on-the-edge-of-oblivion.firstInscriptionDate}}
- First inscription num : {{site.data.on-the-edge-of-oblivion.firstInscriptionNum}}
- Last inscription num : {{site.data.on-the-edge-of-oblivion.lastInscriptionNum}}
- Supply : {{site.data.on-the-edge-of-oblivion.supply}}
- Twitter : {{site.data.on-the-edge-of-oblivion.twitter}}
- Discord : {{site.data.on-the-edge-of-oblivion.discord}}

<div class="grid-container">
    {% for artifact in site.data.on-the-edge-of-oblivion.artifacts  %}
        <div class="grid-item">
            <img src="{{site.url}}/assets/img/on-the-edge-of-oblivion.png" width="100" height="100"/><br>
            <a href="https://ordinals.com/inscription/{{artifact.inscriptionId}}" target="_blank">{{ artifact.artifactId }}</a>
        </div>
    {% endfor %}
</div>