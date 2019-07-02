---
title: "TICKS white paper - Suggested measures for deploying IIIF in Swiss cultural heritage institutions - Version 1.0"
excerpt: "The white paper titled 'Suggested measures for deploying IIIF in Swiss cultural heritage institutions' was published on May 29th as part of the Towards IIIF-Compliance Knowledge in Switzerland (TICKS) project. Its main parts were presented on the occasion of the 2019 IIIF Conference on Wednesday 26th June at one of the lightning talk sessions in Göttingen, Germany."
toc: true
toc_label: "Table of Contents"
categories:
  - posts
tags:
  - IIIF
  - Switzerland
  - Library and Information Science
  - TICKS
  - White paper
date: 2019-07-01 12:00:42 +0100
---

![TICKS Logo][ticks-logo]

## Rationale

As part of the [Towards IIIF-Compliance Knowledge in Switzerland](https://campus.hesge.ch/id_bilingue/projekte/ticks/index_fr.asp) (TICKS) project, a white paper titled ["Suggested measures for deploying IIIF in Swiss cultural heritage institutions"](https://doi.org/10.5281/zenodo.2640415) was released on May 29th 2019. This project originated on the acknowledgements that the [International Image Interoperability Framework](https://iiif.io/) (IIIF - 'triple-eye-eff') ecosystem was not enough known and deployed in the cultural heritage field in Switzerland.

This short blog post provides information on the main components of the white paper. These same indications were presented on the occasion of the 2019 IIIF Conference on Wednesday 26th June at one of the [lightning talk sessions](https://iiif.io/event/2019/goettingen/wednesday/) in Göttingen, Germany - ["Swiss institutions climbing up the IIIF ladder"](https://doi.org/10.5281/zenodo.3238160). 

### Abstract's abstract

_The white paper starts with the main principles of the IIIF, notably indicating the [different technical specifications](https://iiif.io/api/), or application programming interfaces (APIs), produced by the [IIIF community](https://iiif.io/community/) as well as the platforms of Swiss projects or institutions that have deployed IIIF. Going from general to specific, a generic [IIIF step-by-step graph](https://campus.hesge.ch/id_bilingue/projekte/ticks/assets/step_by_step.svg) and six more precise use cases reflecting different needs of the GLAM (Galleries, Libraries, Archives, Museums) sector giving implementation measures have been produced._ 

_Finally, the document contains recommendations for further action as well as some information on the possible reuse of this document for other regions of the world or for other scientific fields._

### Friedrich Washbar

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.2640416.svg)](https://doi.org/10.5281/zenodo.2640416)

The first version of the TICKS white paper is called 'Friedrich Washbar'. It was so named because we had the IIIF event in the Friedrich Dürrenmatt room of the Swiss National Library and because we found a place called the Washbar...

<blockquote class="twitter-tweet"><p lang="en" dir="ltr"><a href="https://twitter.com/hashtag/iiifbern?src=hash&amp;ref_src=twsrc%5Etfw">#iiifbern</a> post-event drinks (but we do have discussion about <a href="https://twitter.com/hashtag/IIIF?src=hash&amp;ref_src=twsrc%5Etfw">#IIIF</a>) <a href="https://t.co/AVzEdQlw1m">pic.twitter.com/AVzEdQlw1m</a></p>&mdash; Julien A. Raemy (@julsraemy) <a href="https://twitter.com/julsraemy/status/1128690845228703744?ref_src=twsrc%5Etfw">May 15, 2019</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script> 

## Main components 

This post focuses on the following four sections: 

- The IIIF ecosystem
- IIIF step-by-step
- Use cases and suggested measures
- Further recommendations 

### The IIIF ecosystem

The first important part of the white paper is called "The IIIF ecosystem" and attempts to answer the following questions:  **what, who, where and when?**. 

In this section, the usual introductions (the IIIF community, APIs, compatible software, etc.) have been integrated. It should be noted, however, that this part is in fact relatively short. To overcome this, small red boxes with a IIIF logo containing useful links are scattered throughout the white paper.

![wp-ecosystem][wp-ecosystem]

### IIIF step-by-step

The IIIF step-by-step diagram gives a generic approach to implement IIIF, which mainly takes into account the instructions up to the implementation of the Presentation API.

![TICKS Logo][ticks-steps]

An SVG version of the IIIF step-by-step diagram can be downloaded [on the Zenodo platform](https://zenodo.org/record/2640416/files/RAEMY_SCHNEIDER_TICKS_IIIF%20Step-by-Step_v1_1_logos.svg?download=1) or can be viewed at the following URL: <https://campus.hesge.ch/id_bilingue/projekte/ticks/assets/step_by_step.svg>. 

### Use cases and suggested measures

This section answers the following questions: "to whom and how?". There are of course some biases in the recommendations, for example software or the way to create IIIF Manifests.

The six case studies in the white paper are as follows:

1. A  platform  specialised  in  the  description and dissemination of  images of  ancient  books  and manuscripts seeking to adapt to IIIF specifications.
2. A  researcher  wanting  to  create her/hisown  IIIF  manifests   with  images   from  various institutions (and publish them on her/his own website).
3. A museum seeking to deploy a IIIF-compliant annotation server to enable their end-users to have a richer experience.
4. A  newspaper  project  seeking  to  disseminate  its  journals  by  allowing  users  to  navigate  by publication date or issue number directly on a IIIF-compliant viewer.
5. An archive that needs to publish its digitised resources in accordance with the classification of the collection while restricting access to sensitive resources.
6. A platform mainly dedicated to the diffusion of audio-visual materials showing interest in the IIIF Presentation API 3.0.

Each use case is divided into five parts and is composed of the following elements: 1) context, background, tier, implementation effort, APIs to implement, 2) success story, 3) recommendations, 4) useful links, 5) IIIF point of contact such as on the IIIF Community or Technical Specification Groups.

![wp-usecases][wp-usecases]

### Further recommendations

For almost all institutions, IIIF is often included in a broader spectrum and it is necessary to imagine that the use cases or the implementation of specifications within a system is much more complex. That is why a section titled "further recommendations" has been created. It contains the following subsections:  

* Tips for small institutions
* Discovering the IIIF universe
* Persistent identifiers (PIDs)
* The IIIF Cookbook

![wp-further][wp-further]

## Perspectives
### TICKS white paper - future versions

The purpose of this white paper is to be updated as regularly as possible when technical specifications change, for instance, or even to be adapted to other regions or scientific disciplines. It would also be very useful to translate parts or the entire document into the Swiss official languages (German, French, Italian).

Since this document could not have been produced without the help of the wider IIIF community, they would also have to support me with a new version. One way to help me is to comment directly on the Google Doc version: <http://bit.ly/wpticks>. 

### IIIF in Switzerland

For the moment (and to my knowledge), there are eight IIIF-compatible Swiss platforms: 

* [e-codices](https://e-codices.ch/), the Virtual Manuscript Library of Switzerland, 2263 IIIF Manifests
* [e-manuscripta](https://www.e-manuscripta.ch/), the digital platform for manuscripts material from Swiss libraries and archives, more than 80,000 IIIF Manifests
* [e-rara](https://www.e-rara.ch/), the platform for digitised rare books from Swiss libraries, more than 70,000 IIIF Manifests
* [e-newspaperarchives.ch](https://www.e-newspaperarchives.ch/), collections of digitised Swiss newspapers, 32 public domain titles comprising 280,000 IIIF Manifests
* [Fragmentarium](https://fragmentarium.ms/), Digital Research Laboratory for Medieval Manuscript Fragments, 882 IIIF Manifests
* [Bodmer Lab](https://bodmerlab.unige.ch/), "Une bibliothèque numérique de la littérature mondiale", more than 800 IIIF Manifests (manuscripts and printed books)
* [Plume EPFL](https://plume.epfl.ch/), "collections patrimoniales numérisées de la Bibliothèque de l'EPFL" (precious books, published between the 15th and the 18th centuries, and kept in the EPFL Library), 68 IIIF Manifests (in the future about 600 digitised books will be available on the platform)

![IIIF in Switzerland][map-switzerland]

The number of IIIF-compliant systems in Switzerland should also increase when Image and Presentation APIs 3.x become stable, since it will allow to disseminate audio-visualresources through this medium. It will indeed be interesting to see which organisations will start to take an interest in it and how the IIIF universe can grow. In a nutshell, I would like to see more dots in the above map.

### Communicating IIIF to end-users

It is worth noting that the white paper is intended for GLAM institutions (or rather members of these institutions) who would like to implement IIIF, whether at the organisational level, at a project level or even for individual needs. It has been conceived as well for those who have just implemented IIIF or wish to do so in the near future.

The needs of end-users are only slightly addressed in this document. There is a lack of documentation within the IIIF community to communicate directly the benefits of the framework without going into too much technical detail. Some institutions (e. g. Yale or the University of Cambridge) have nevertheless started to integrate IIIF into pedagogical training courses without necessarily talking about APIs right away or even without talking about IIIF (or at least not in the title of the training).  

It would be very interesting to have more feedback from institutions or individuals who provide training to end users using IIIF-compliant resources. Perhaps we should consider streamlining all of this by pooling relevant information or communicating more regularly, for example through the monthly calls of the [IIIF Outreach Community Group](https://iiif.io/community/groups/outreach/).

### A possible follow-up project

I am thinking about how to carry out a follow-up project and see which institutions would be interested in a TICKS V2 while also relying on the results of the break-out session that happened during the [Bern IIIF Showcase Event](https://campus.hesge.ch/id_bilingue/projekte/ticks/bern-iiif-showcase-event_fr.html) on May 15th (presentations and notes of this event can be found at the following URL address: <http://bit.ly/iiifbern>). The event participants were particularly interested in a platform that would guide institutions wishing to implement IIIF based somewhat on the French approach provided by Biblissima, known as [IIIF360](https://projet.biblissima.fr/en/resources/iiif-360).  

[ticks-logo]: https://julsraemy.github.io/assets/images/ticks.png
[ticks-steps]: https://julsraemy.github.io/assets/images/iiif-step-by-step.jpg
[map-switzerland]: https://julsraemy.github.io/assets/images/iiif-map-switzerland.png 
[wp-ecosystem]: https://julsraemy.github.io/assets/images/wp-ecosystem.png
[wp-usecases]: https://julsraemy.github.io/assets/images/wp-usecases.png
[wp-further]: https://julsraemy.github.io/assets/images/wp-further.png