---
layout: post
title:  "Bitcoin Rocks"
date:   2023-01-23 07:28:47 +0000
firstInscriptionNum: 71
lastInscriptionNum: 161
image: https://ordinals.com/content/e8ce0fcb238b377b3a6b9921333e26fbec5c5724c5bf6e783c3dcc1129794508i0
categories: sub1k
---
- Name : {{site.data.bitcoin-rocks.name}}
- Description : {{site.data.bitcoin-rocks.description}}
- First inscription date : {{site.data.bitcoin-rocks.firstInscriptionDate}}
- First inscription num : {{site.data.bitcoin-rocks.firstInscriptionNum}}
- Last inscription num : {{site.data.bitcoin-rocks.lastInscriptionNum}}
- Supply : {{site.data.bitcoin-rocks.supply}}
- Twitter : {{site.data.bitcoin-rocks.twitter}}
- Discord : {{site.data.bitcoin-rocks.discord}}

<div class="grid-container">
    {% for rock in site.data.bitcoin-rocks.artifacts  %}
        <div class="grid-item">
            <img src="https://ordinals.com/content/{{rock.inscriptionId}}" width="100" height="100"/><br>
            <a href="https://ordinals.com/inscription/{{rock.inscriptionId}}" target="_blank">{{ rock.artifactId }}</a>
        </div>
    {% endfor %}
</div>