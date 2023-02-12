---
layout: post
title:  "Bitcoin Punks"
date:   2023-02-06 03:58:45 +0000
firstInscriptionNum: 1276
lastInscriptionNum: 5530
image: https://ordinals.com/content/1b68a1d4f2957e2d364ae34f8422eb4ab76df5783613af8b6059808a77a46caci0
categories: sub10k
---
- Name : {{site.data.bitcoin-punks.name}}
- Description : {{site.data.bitcoin-punks.description}}
- First inscription date : {{site.data.bitcoin-punks.firstInscriptionDate}}
- First inscription num : {{site.data.bitcoin-punks.firstInscriptionNum}}
- Last inscription num : {{site.data.bitcoin-punks.lastInscriptionNum}}
- Supply : {{site.data.bitcoin-punks.supply}}
- Twitter : {{site.data.bitcoin-punks.twitter}}
- Discord : {{site.data.bitcoin-punks.discord}}

<div class="grid-container">
    {% for rock in site.data.bitcoin-punks.artifacts  %}
        <div class="grid-item">
            <img src="https://ordinals.com/content/{{rock.inscriptionId}}" width="100" height="100"/><br>
            <a href="https://ordinals.com/inscription/{{rock.inscriptionId}}" target="_blank">{{ rock.artifactId }}</a>
        </div>
    {% endfor %}
</div>