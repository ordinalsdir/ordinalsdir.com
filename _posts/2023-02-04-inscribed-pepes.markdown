---
layout: post
title:  "Inscribed Pepes"
date:   2023-02-04 20:27:34 +0000
firstInscriptionNum: 71
lastInscriptionNum: 161
image: https://ordinals.com/content/ba698535dc15c8761bf276b8938fc60e118587d25cb92c4104c45ab4ac9a1bcbi0
categories: sub1k
---
- Name : {{site.data.inscribed-pepes.name}}
- Description : {{site.data.inscribed-pepes.description}}
- First inscription date : {{site.data.inscribed-pepes.firstInscriptionDate}}
- First inscription num : {{site.data.inscribed-pepes.firstInscriptionNum}}
- Last inscription num : {{site.data.inscribed-pepes.lastInscriptionNum}}
- Supply : {{site.data.inscribed-pepes.supply}}
- Twitter : {{site.data.inscribed-pepes.twitter}}
- Discord : {{site.data.inscribed-pepes.discord}}

<div class="grid-container">
    {% for rock in site.data.inscribed-pepes.artifacts  %}
        <div class="grid-item">
            <img src="https://ordinals.com/content/{{rock.inscriptionId}}" width="100" height="100"/><br>
            <a href="https://ordinals.com/inscription/{{rock.inscriptionId}}" target="_blank">{{ rock.artifactId }}</a>
        </div>
    {% endfor %}
</div>