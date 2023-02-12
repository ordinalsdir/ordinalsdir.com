---
layout: post
title:  "Ordinal Punks"
date:   2023-02-01 10:17:24 +0000
firstInscriptionNum: 411
lastInscriptionNum: 642
image: https://ordinals.com/content/96d87d7e59d75ebc0e6144b09fdd96355fcdaa86fd098d64c46f19a424012bbei0
categories: sub1k
---
- Name : {{site.data.ordinal-punks.name}}
- Description : {{site.data.ordinal-punks.description}}
- First inscription date : {{site.data.ordinal-punks.firstInscriptionDate}}
- First inscription num : {{site.data.ordinal-punks.firstInscriptionNum}}
- Last inscription num : {{site.data.ordinal-punks.lastInscriptionNum}}
- Supply : {{site.data.ordinal-punks.supply}}
- Twitter : {{site.data.ordinal-punks.twitter}}
- Discord : {{site.data.ordinal-punks.discord}}

<div class="grid-container">
    {% for rock in site.data.ordinal-punks.artifacts  %}
        <div class="grid-item">
            <img src="https://ordinals.com/content/{{rock.inscriptionId}}" width="100" height="100"/><br>
            <a href="https://ordinals.com/inscription/{{rock.inscriptionId}}" target="_blank">{{ rock.artifactId }}</a>
        </div>
    {% endfor %}
</div>