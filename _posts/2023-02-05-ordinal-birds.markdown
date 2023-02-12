---
layout: post
title:  "Ordinal Birds"
date:   2023-02-05 01:07:25 +0000
firstInscriptionNum: 2728
lastInscriptionNum: 4816
image: https://ordinals.com/content/0a6bb0887af1ced974f141ee2bc93022df8eb0402b6982b3fd9fcddcb7462a87i0
categories: sub10k
---
- Name : {{site.data.ordinal-birds.name}}
- Description : {{site.data.ordinal-birds.description}}
- First inscription date : {{site.data.ordinal-birds.firstInscriptionDate}}
- First inscription num : {{site.data.ordinal-birds.firstInscriptionNum}}
- Last inscription num : {{site.data.ordinal-birds.lastInscriptionNum}}
- Supply : {{site.data.ordinal-birds.supply}}
- Twitter : {{site.data.ordinal-birds.twitter}}
- Discord : {{site.data.ordinal-birds.discord}}

<div class="grid-container">
    {% for rock in site.data.ordinal-birds.artifacts  %}
        <div class="grid-item">
            <img src="https://ordinals.com/content/{{rock.inscriptionId}}" width="100" height="100"/><br>
            <a href="https://ordinals.com/inscription/{{rock.inscriptionId}}" target="_blank">{{ rock.artifactId }}</a>
        </div>
    {% endfor %}
</div>