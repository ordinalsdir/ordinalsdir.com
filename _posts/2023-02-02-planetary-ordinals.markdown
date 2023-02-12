---
layout: post
title:  "Planetary Ordinals"
date:   2023-02-02 08:41:49 +0000
firstInscriptionNum: 489
lastInscriptionNum: 997
image: https://ordinals.com/content/af0b19432a676551223e300e7197348b7c225cb7b31d0d7c6e246e382cbf6f81i0
categories: sub10k
---
- Name : {{site.data.planetary-ordinals.name}}
- Description : {{site.data.planetary-ordinals.description}}
- First inscription date : {{site.data.planetary-ordinals.firstInscriptionDate}}
- First inscription num : {{site.data.planetary-ordinals.firstInscriptionNum}}
- Last inscription num : {{site.data.planetary-ordinals.lastInscriptionNum}}
- Supply : {{site.data.planetary-ordinals.supply}}
- Twitter : {{site.data.planetary-ordinals.twitter}}
- Discord : {{site.data.planetary-ordinals.discord}}

<div class="grid-container">
    {% for rock in site.data.planetary-ordinals.artifacts  %}
        <div class="grid-item">
            <img src="https://ordinals.com/content/{{rock.inscriptionId}}" width="100" height="100"/><br>
            <a href="https://ordinals.com/inscription/{{rock.inscriptionId}}" target="_blank">{{ rock.artifactId }}</a>
        </div>
    {% endfor %}
</div>