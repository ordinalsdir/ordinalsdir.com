---
layout: post
title: "Bitcoin Checks"
date: 2023-02-09 01:14:05 +0000
firstInscriptionNum: 40711
lastInscriptionNum: 44603
image: https://ordinals.com/content/9baec9ddc23c7ca62d06891a72f08f74f97dada8e384413a2de1a694f6e10b1bi0
categories: sub100k
---

- Name : {{site.data.bitcoin-checks.name}}
- Description : {{site.data.bitcoin-checks.description}}
- First inscription date : {{site.data.bitcoin-checks.firstInscriptionDate}}
- First inscription num : {{site.data.bitcoin-checks.firstInscriptionNum}}
- Last inscription num : {{site.data.bitcoin-checks.lastInscriptionNum}}
- Supply : {{site.data.bitcoin-checks.supply}}
- Twitter : {{site.data.bitcoin-checks.twitter}}
- Discord : {{site.data.bitcoin-checks.discord}}

<div class="grid-container">
    {% for rock in site.data.bitcoin-checks.artifacts  %}
        <div class="grid-item">
            <img src="https://ordinals.com/content/{{rock.inscriptionId}}" width="100" height="100"/><br>
            <a href="https://ordinals.com/inscription/{{rock.inscriptionId}}" target="_blank">{{ rock.artifactId }}</a>
        </div>
    {% endfor %}
</div>
