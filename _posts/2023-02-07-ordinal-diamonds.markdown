---
layout: post
title:  "Ordinal Diamonds"
date:   2023-02-07 08:21:56  +0000
image: https://ordinals.com/content/c343f391503cb55e0d505a2dddd0cf6f56ad43c44d11c52477a3ed026e1dd403i0
categories: sub100k
---
- Name : {{site.data.ordinal-diamonds.name}}
- Description : {{site.data.ordinal-diamonds.description}}
- First inscription date : {{site.data.ordinal-diamonds.firstInscriptionDate}}
- First inscription num : {{site.data.ordinal-diamonds.firstInscriptionNum}}
- Last inscription num : {{site.data.ordinal-diamonds.lastInscriptionNum}}
- Supply : {{site.data.ordinal-diamonds.supply}}
- Twitter : {{site.data.ordinal-diamonds.twitter}}
- Discord : {{site.data.ordinal-diamonds.discord}}

<div class="grid-container">
    {% for rock in site.data.ordinal-diamonds.artifacts  %}
        <div class="grid-item">
            <img src="https://ordinals.com/content/{{rock.inscriptionId}}" width="100" height="100"/><br>
            <a href="https://ordinals.com/inscription/{{rock.inscriptionId}}" target="_blank">{{ rock.artifactId }}</a>
        </div>
    {% endfor %}
</div>