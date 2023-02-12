---
layout: post
title:  "Ordinatus"
date:   2023-02-07 03:00:21 +0000
firstInscriptionNum: 9400
lastInscriptionNum: 17788
image:  https://ordinals.com/content/25f49bb3f86e57acded4db92fb8a67185369f05928c499210a0527726461264fi0
categories: sub10k
---
- Name : {{site.data.ordinatus.name}}
- Description : {{site.data.ordinatus.description}}
- First inscription date : {{site.data.ordinatus.firstInscriptionDate}}
- First inscription num : {{site.data.ordinatus.firstInscriptionNum}}
- Last inscription num : {{site.data.ordinatus.lastInscriptionNum}}
- Supply : {{site.data.ordinatus.supply}}
- Twitter : {{site.data.ordinatus.twitter}}
- Discord : {{site.data.ordinatus.discord}}

<div class="grid-container">
    {% for rock in site.data.ordinatus.artifacts  %}
        <div class="grid-item">
            <img src="https://ordinals.com/content/{{rock.inscriptionId}}" width="100" height="100"/><br>
            <a href="https://ordinals.com/inscription/{{rock.inscriptionId}}" target="_blank">{{ rock.artifactId }}</a>
        </div>
    {% endfor %}
</div>