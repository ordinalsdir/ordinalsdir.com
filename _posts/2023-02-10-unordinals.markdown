---
layout: post
title:  "Unordinals"
date:   2023-02-10 01:14:05 +0000
image: https://ordinals.com/content/93cf8a87f4e006c3fc19b0bd4b1ab189abe652744231bd8eb18008064a970d08i0
categories: sub100k
---
- Name : {{site.data.unordinals.name}}
- Description : {{site.data.unordinals.description}}
- First inscription date : {{site.data.unordinals.firstInscriptionDate}}
- First inscription num : {{site.data.unordinals.firstInscriptionNum}}
- Last inscription num : {{site.data.unordinals.lastInscriptionNum}}
- Supply : {{site.data.unordinals.supply}}
- Twitter : {{site.data.unordinals.twitter}}
- Discord : {{site.data.unordinals.discord}}

<div class="grid-container">
    {% for rock in site.data.unordinals.artifacts  %}
        <div class="grid-item">
            <img src="https://ordinals.com/content/{{rock.inscriptionId}}" width="100" height="100"/><br>
            <a href="https://ordinals.com/inscription/{{rock.inscriptionId}}" target="_blank">{{ rock.artifactId }}</a>
        </div>
    {% endfor %}
</div>