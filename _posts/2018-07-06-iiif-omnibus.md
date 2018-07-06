---
title: "IIIF Omnibus - looking back at the 2018 IIIF Conference in Washington D.C."
excerpt: "The 2018 IIIF Conference took place in Washington D.C. between May 21 and 25. It was co-hosted by the Library of Congress, the Simthsonian Institution, and the Folger Shakespeare Library. In this blogpost are listed some of my best highlights of the conference."
toc: true
toc_label: "Table of Contents"
categories:
  - posts
tags:
  - IIIF
  - Conference
  - Washington D.C.
  - Library of Congress
  - Smithsonian Institution
  - Folger Shakespeare Library
  - Library and Information Science
  - Digital Humanities
  - TICKS
date: 2018-07-06 15:52:00 +0100
---

![2018 IIIF Logo][2018iiif]

## Foreword

Hello there! Here is small blog post about the 2018 IIIF Conference which I had the chance to attend. The event took place in Washington D.C. between May 21 and 25 and was jointly hosted by the Library of Congress, the Smithsonian Institution, and the Folger Shakespeare Library. 

If you've never heard of the [International Image Interoperability Framework][iiif] (IIIF - pronounced "triple-eye-eff"), I recommend you take a look at these two very useful resources:

- [Getting started with IIIF][intro-iiif], originally presented by Jack Reed and Drew Winget (Stanford University) during a workshop at the 2017 Code4Lib Conference in Los Angeles, CA
- [An introduction to IIIF][intro-crane] by Tom Crane, Technical Director at Digirati and one of the IIIF Editors.

And if you don't feel confident enough to read these resources in English, here are a couple of things in three other languages:

- in German
  - [An introduction to IIIF][iiif-german] by Rafael Schwemmer from text&bytes 
  - [Das International Image Interoperability Framework (IIIF): ein neuer Standard für Zusammenarbeit, Nutzerfreundlichkeit und Forschung][iiif-mdz] by the BSB (Bayerische StaatsBibliothek) team
- in French
  - [Introduction à IIIF][iiif-biblissima] and [Comprendre IIIF et l’interopérabilité des bibliothèques numériques][comprendre-iiif] by Régis Robineau from Biblissima
  - [Interopérabilité des images : de la nécessité des tests d’utilisabilité][ressi-iiif] and [IIIF ou comment enfin valoriser ses images numériques de manière optimale et interopérable][arodes-iiif] by myself
- in Portuguese
  - [Conhecendo o IIIF — Padrões e ferramentas para publicação de imagens na web][germani-medium] by Leo Germani

_I am sorry about the imbalance between the different blocks. As the conference progressed, I took fewer notes. I hold Washington D.C. and its bars responsible. I  punctuated this post with a lot of tweets and images as I didn't want to bore you (and also because most things are better said by others)._

## Why I went to the 2018 IIIF Conference

Six weeks* ago I was in Washington D.C. for the [2018 IIIF Conference][2018-iiif] to meet the usual suspects ("IIIFers") as well as new folks from this amazing and growing community. The reasons were threefold:

1. As part of the Program Committee, I couldn't miss an event that we started organizing in December. Speaking of which, it was a great, but time-consuming, experience. 
2. I had a 20-minute presentation on Thursday, May 24th at the Library of Congress about Towards IIIF-Compliance Knowledge in Switzerland [(TICKS)][ticks-rg], the project that René Schneider, the professor I work with in Geneva, and myself have been conducting. I swear that I haven't reviewed my own proposal. :innocent:
3. I love the social events and informal activities happening around this community. :beers: 

*Note: By the way, it took me four weeks to finish this small blog post. So the introduction used to be "three weeks ago..."*

## The workshops

On the [Monday][2018-monday], we had pre-conference workshops at the S. Dillon Ripley Center, which is near the Smithsonian Castle. I chose to follow:

- *Train the Trainer and IIIF Awesome* in the morning 
- *IIIF and Annotations* in the afternoon

### Train the Trainer

[Jason Ronallo][ronallo], Department Head of Digital Library Initatives at the North Carolina State University (NCSU) Libraries, started his Train the trainer workshop (titled here "[Teaching with IIIF][ronallo-teaching]") by asking participants to consider these five key questions:

1. What 1-3 things have you learned from teaching IIIF?
2. What are the challenges to teaching IIIF?
3. What are effective approaches? What's most convincing? What has wowed folks?
4. What questions have you gotten?
5. What resources did you use? What's missing?

I sadly didn't take any notes, but there should be a couple of things that I should be able to recall! Jason and other participants (Emma Stanford from the University of Oxford's [Bodleian Libraries][digital-bod], Sophie Dixon from [Mnemoscene][mnemo], and someone I can't remember) shared with us their experience and gave us their tips as well as ideas on how to run training sessions around IIIF. It was a great 

I really like the visual aspect of Jason's [new version of the workshop][ronallo-workshop] which contains tips, checkmarks, copy-paste fallbacks as well as bonus material and challenge exercices. For the latter, I see it as a real added value because if it's already hard to manage participants who are in difficulty, it is even more challenging (in my opinion) to satisfy people who find the exercises too easy and who might get bored. Emma suggested to create ready-to-go toolkits such as HTML5 templates (pointing to an instance of Mirador) for academics who don't have time to understand how to publish IIIF manifests. Sophie talked about her experience on how Omeka can enhance accessibility of smaller archives project, notably with the integration of the [Universal Viewer][uv].

We didn't really have time to go though all of Jason's slides before the morning break. I would have liked it to be slightly longer but I reckon that we did cover most aspects of the workshop. I wonder if next time people could simulate a part of a lesson/worksho/seminar on IIIF.

After the break, Jason talked about the [Awesome IIIF list][awesome-iiif] that is available on GitHub and we went through some issues and pull resquests as a group. I really liked the hands-on approach of [this workshop][ronallo-awesome]. We can also count on new curators of awesome! -- Please join the crew!

### IIIF and Annotations

After lunch, Matt McGrattan, Head of Digital Library Solutions at [Digirati][digirati], conducted the [IIIF and Annotations][matt-anno] workshop. I chose to do this one in the afternoon because I really want to understand how institutions and inviduals want to implement an annotations server and how they want the annotations to be curated.

There wasn't a fixed agenda (as stated in <https://mattmcgrattan.github.io/Washington%20Annotation%20Workshop/Agenda.html>) but here were the different (and possible) topics that this workshop encompassed:

- IIIF & Annotations 
- W3C Model and Protocol
- Annotation Servers & Clients
- Show & Tell
- Use Cases
- Problems
- Cookbook

 It was a very interesting session where some participants talked about their [use cases][anno-usecases] and the way they want annotations to be handled within the IIIF ecosystem in terms of user experience, authentication, discovery and notification, preservation and versioning, as well as semantics aspects.

 I really liked the emphasis on user experience (who wouldn't?) and I am curious to see if the IIIF Community could provide enough good recipes around annotations in the cookbook. :point_right: please add any cookbook entries here: <https://github.com/IIIF/api/issues/1409>.

## The IIIF Showcase

On a rainy and stormy Tuesday there was a showcase. 

[The IIIF Showcase][2018-tuesday] was a free event that took place in the Library of Congress Coolidge Auditorium on May 22. [Kate Zwaard][kzwa], Director of Digital Strategy at the LoC, opened the showcase by giving a great speach on how the IIIF ecosystem could empower end users. She also acknowledged the great work done by institutions and inviduals from the IIIF community. 

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">.<a href="https://twitter.com/kzwa?ref_src=twsrc%5Etfw">@kzwa</a> introduces the <a href="https://twitter.com/hashtag/iiif?src=hash&amp;ref_src=twsrc%5Etfw">#iiif</a> showcase <a href="https://t.co/hIuGrfoLvL">pic.twitter.com/hIuGrfoLvL</a></p>&mdash; Julien A. Raemy (@julsraemy) <a href="https://twitter.com/julsraemy/status/998927548959555584?ref_src=twsrc%5Etfw">May 22, 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">.<a href="https://twitter.com/kzwa?ref_src=twsrc%5Etfw">@kzwa</a> points to tool development as essential community work that builds capacity in cultural heritage institutions <a href="https://twitter.com/hashtag/IIIF?src=hash&amp;ref_src=twsrc%5Etfw">#IIIF</a></p>&mdash; Meaghan Brown (@EpistolaryBrown) <a href="https://twitter.com/EpistolaryBrown/status/998928558641868800?ref_src=twsrc%5Etfw">May 22, 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">.<a href="https://twitter.com/kzwa?ref_src=twsrc%5Etfw">@kzwa</a> acknowleding the intellectual, professional, and emotional labor that goes into community work = fantastic &lt;3 <a href="https://twitter.com/hashtag/iiif?src=hash&amp;ref_src=twsrc%5Etfw">#iiif</a></p>&mdash; oo (@anarchivist) <a href="https://twitter.com/anarchivist/status/998928831712055296?ref_src=twsrc%5Etfw">May 22, 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

After being welcomed by Kate Zwaard, we had our (now) traditional presentation from Tom Cramer, Assistant University Librarian and Chief Technoly Strategist at Stanford University, who didn't miss an opportunity to talk about the cultural heritage sector before (or without) IIIF represented by the silos.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">And now the famous Silo image <a href="https://twitter.com/hashtag/IIIF?src=hash&amp;ref_src=twsrc%5Etfw">#IIIF</a> cc <a href="https://twitter.com/tcramer?ref_src=twsrc%5Etfw">@tcramer</a> <a href="https://t.co/kdkK8qU0Ca">pic.twitter.com/kdkK8qU0Ca</a></p>&mdash; Julien A. Raemy (@julsraemy) <a href="https://twitter.com/julsraemy/status/998930211537383424?ref_src=twsrc%5Etfw">May 22, 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

Here is the link to the Silo picture (_Grain elevators, Calwell, Idaho_ by Russell Lee taken in 1941): <https://www.flickr.com/photos/library_of_congress/2178285893> (which is held at the Library of Congress!)

Last March, I was in Paris at the IIIF event that Biblissima organised and some IIIFers thought it'd be a good idea to create a gif. Here is my small contribution (with images taken from presentations given by many individuals from the IIIF community):

![Breaking silos with IIIF][silos-to-iiif]

The rest of the IIIF Showcase was programmed this way:

- IIIF Community Use cases
- Panel: What does the future look like with interoperable collections?
- APIs, viewers and A/V
- Community, Consortium and fun with IIIF
- Commercial support and innovations

By the way, the IIIF showcase was recorded and all presentations should be at some point available on the [IIIF Youtube channel][youtube-iiif].

During the entire Showcase, we had two American Sign Language (ASL) interpreters and I was fascinated. I was obvisously not the only person.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">The two unsung hero’s of <a href="https://twitter.com/hashtag/IIIF?src=hash&amp;ref_src=twsrc%5Etfw">#IIIF</a> today are the two indefatigable ASL interpreters — we talk often about invisible labour, it’s been seriously impressive watching them all day!! <a href="https://t.co/7Ssi6omtLm">pic.twitter.com/7Ssi6omtLm</a></p>&mdash; Anne McLaughlin (@anmcl001) <a href="https://twitter.com/anmcl001/status/999028865052880896?ref_src=twsrc%5Etfw">May 22, 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

And when I said "rainy and stormy Tuesday", I wasn't kidding at all. Here is the video that Tom Cramer captured near the Library of Congress just after the IIIF Showcase: 

<iframe width="320" height="568" src="https://julsraemy.github.io/assets/videos/DCRain_Cramer.mov" frameborder="0" allowfullscreen></iframe>

_All the great presentations from the Showcase and the Conference can be found in a [dedicated directory][2018-presentations] of the IIIF Google Drive._

## The 2018 IIIF Conference

I can't remember the number of partipants who were new to IIIF, that it was actually pretty high for the IIIF Showcase and the proportion was a little bit lower for the Conference.

The first day of the conference happened like Tuesday at the Library of Congress Coolidge Auditorium in the Jefferson Building (plenary) and the two other days in the Madison Building (parallel sessions).

### Plenary conference on Wednesday, May 23 

On [Wednesday][2018-wed], we started the plenary conference with these two blocks: 
- IIIF Community Group Updates
- Technical Sepcification Status Update

For each of these sessions, we had one co-chair per group who talked five to ten minutes and some time for the audience to ask questions at the end. To me, the highlight was of course this great slide from Rob Sanderson talking about cross version usage of IIIF APIs:

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">A fair representation of the <a href="https://twitter.com/hashtag/IIIF?src=hash&amp;ref_src=twsrc%5Etfw">#IIIF</a> editors if you want to use Presentation API 3 manifests with Image API 2 cc <a href="https://twitter.com/azaroth42?ref_src=twsrc%5Etfw">@azaroth42</a> <a href="https://twitter.com/jpstroop?ref_src=twsrc%5Etfw">@jpstroop</a> <a href="https://twitter.com/zimeon?ref_src=twsrc%5Etfw">@zimeon</a> <a href="https://twitter.com/mikeapps?ref_src=twsrc%5Etfw">@mikeapps</a> <a href="https://twitter.com/tomofhernehill?ref_src=twsrc%5Etfw">@tomofhernehill</a> <a href="https://t.co/OPQJVLmqsE">pic.twitter.com/OPQJVLmqsE</a></p>&mdash; Julien A. Raemy (@julsraemy) <a href="https://twitter.com/julsraemy/status/999294348830429184?ref_src=twsrc%5Etfw">May 23, 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

After the break, the lightning talks started and my goodness these were all great! But again, here are the ones I really appreciated:
 - Emma Stanford's Packing Light: Building the Bodleian's metadata block :point_right: I like the emphasis on best practices on how metadata manifests should look like once displayed in a IIIF viewer 
 - Visualizing which parts of IIIF images are looked by users by Chifumi Nishioka (Kyoto University) and Kiyonori Nagasaki (University of Tokyo) :point_right: I really loved the use of heatmaps. It was a very interesting machine learning study conducted by the two Japanese universities.
 - Going beyond the viewer by Jack Reed (Stanford University) :point_right: who wouldn't want to have high-resolution maps on their Apple TV?
 - GLAM2IIIF: Papering over the cataloguing gaps by Richard Palmer (Victoria and Albert Museum) :point_right: I mean what the V&A does always amazes me and also Richard found great titles to each of his slides.
 - Marri Nyröp (Columbia University Libraries) gave a great last lightning talk on [Wax, "a minimal IIIF exhibitions with Jekyll"][wax] :point_right: Great ways for students and small institutions to create a IIIF-compliant website and to learn how to use git

 <blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Final talk of the day: <a href="https://twitter.com/mariinyrop?ref_src=twsrc%5Etfw">@mariinyrop</a> on wax and &quot;minimal <a href="https://twitter.com/hashtag/IIIF?src=hash&amp;ref_src=twsrc%5Etfw">#IIIF</a>&quot;. wax produces static scholarly exhibitions w/ minimal computing principles--chimes w/ <a href="https://twitter.com/danieltbrennan?ref_src=twsrc%5Etfw">@danieltbrennan</a>&#39;s and <a href="https://twitter.com/tomofhernehill?ref_src=twsrc%5Etfw">@tomofhernehill</a>&#39;s talks.</p>&mdash; Emma Stanford (@e_stanf) <a href="https://twitter.com/e_stanf/status/999388653246967808?ref_src=twsrc%5Etfw">May 23, 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

### Parallel sessions on Thursday and Friday, May 24-25

On [Thursday][2018-thursday], I was pretty nervous as I was the first to present [TICKS][ticks-zenodo], my little project on how to persuade Swiss institutions to go IIIF, in the Dining Room A. 

After my presentation, I went mostly the ones that the editors convened (let's ratify, hell yeah!):

- Discussion of Process to Register IIIF API Extensions
- Discussion and Ratification of Version 3.0 Image and Presentation APIs

Here are the [notes][notes-dc] of these sessions.

In the afternoon, I also went to the A/V presentations in the Montpelier room, especially to listen to my mate Andy and the way the British Library will handle the massive audiovisual collection they have.

On [Friday][2018-friday], I was naturally a little bit sad as it was the last day of a great (and mostly sunny and warm) conference. Because I had some trouble with my credit card, I actually missed most of the presentations and managed to see just the end of "Implementing all of the APIs, lessons learned and challenges tackled" in the Dining Room A. 

I went then to the Montpelier room again to witness three great presentations:

- ‘All the World’s a Stage’: Diverse case studies for IIIF at the Folger Shakespeare Library by Stacey Redick and Meaghan Brown :point_right: I really like the different use cases and user stories that the Folger have come up with to enhance Miranda, their platform to "rule them all" 
- Improving Access to Primary Sources of Law with IIIF by Mark Matney (University of California, Los Angeles) :point_right: intersting use of Ocracoke to build proof of concept of IIIF in the context of legal documents
- Beyond the viewer: more windows on our shared digital space by Tom Crane (Digirati) :point_right: amazing presentation about Digirati's Canvas Panel creating "the IIIF round trip experience" which is better explained by its author in [this blog post][crane-beyond]

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">.<a href="https://twitter.com/staceyrdk?ref_src=twsrc%5Etfw">@staceyrdk</a> and <a href="https://twitter.com/EpistolaryBrown?ref_src=twsrc%5Etfw">@EpistolaryBrown</a> and their &quot;simple list of use cases&quot; <a href="https://twitter.com/hashtag/IIIF?src=hash&amp;ref_src=twsrc%5Etfw">#IIIF</a> <a href="https://twitter.com/FolgerLibrary?ref_src=twsrc%5Etfw">@FolgerLibrary</a> <a href="https://t.co/BVDHAJLMZS">pic.twitter.com/BVDHAJLMZS</a></p>&mdash; Julien A. Raemy (@julsraemy) <a href="https://twitter.com/julsraemy/status/1000033779476549632?ref_src=twsrc%5Etfw">May 25, 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

Due to Memoriay Day Weekend in the USA, the conference closed at lunch time. Some of us went to have a look at the Library of Congress wonders. We were guided by one very knowledgeable LoC staff member (I can't remember his name though). 

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Here are some of the pictures I took at <a href="https://twitter.com/librarycongress?ref_src=twsrc%5Etfw">@librarycongress</a> during the tour following the 2018 <a href="https://twitter.com/hashtag/IIIF?src=hash&amp;ref_src=twsrc%5Etfw">#IIIF</a> Conference <a href="https://t.co/uZLKXtUHtk">pic.twitter.com/uZLKXtUHtk</a></p>&mdash; Julien A. Raemy (@julsraemy) <a href="https://twitter.com/julsraemy/status/1000107564305174528?ref_src=twsrc%5Etfw">May 25, 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script> 

## Receptions and other great social activities

On Tuesday, we the chance to go to the Folger Shakespeare  for a wine reception with light fare (light? They served an excellent and large buffet) just after the IIIF Showcase. 

Before going to the reception, I went back to my airbnb, changed my soaked clothes and eventually decided that I should always have an umbrella by my side!

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">And finally, last but certainly not least the Folger Shakespeare Library. Location of the Tuesday Showcase reception. <a href="https://twitter.com/hashtag/iiif?src=hash&amp;ref_src=twsrc%5Etfw">#iiif</a> Washington Conference. <a href="https://t.co/IARt7bzshD">pic.twitter.com/IARt7bzshD</a></p>&mdash; Glen Robson (@glenrobson) <a href="https://twitter.com/glenrobson/status/998303611858903040?ref_src=twsrc%5Etfw">May 20, 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<blockquote class="twitter-tweet" data-lang="en"><p lang="ja" dir="ltr">IIIF会議のレセプション。Folger Shakespeare Library. <a href="https://t.co/yZ1LJJcFX0">pic.twitter.com/yZ1LJJcFX0</a></p>&mdash; Center for Open Data in the Humanities (CODH) (@rois_codh) <a href="https://twitter.com/rois_codh/status/999179543574470656?ref_src=twsrc%5Etfw">May 23, 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

On Wednesday, we had a really great reception at the Smithsonian Castle (well not a castle by European standards, but still a very beautiful and impressive mansion I reckon).

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Just walking round some of the <a href="https://twitter.com/hashtag/iiif?src=hash&amp;ref_src=twsrc%5Etfw">#iiif</a> conference venues. This is the amazing Smithsonian Castle location of Wednesday’s reception. <a href="https://t.co/wtFT41nznO">pic.twitter.com/wtFT41nznO</a></p>&mdash; Glen Robson (@glenrobson) <a href="https://twitter.com/glenrobson/status/998287199656468481?ref_src=twsrc%5Etfw">May 20, 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

Other days nothing was officially planned but with a couple of amazing IIIFers, we decided on Thursday to go to Muzette, a nice Korean karaoke with private booths. We hope that when the Presentation API 3.0 will be implemented, that every institution will organize IIIF-based karaokes!

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Taking the new <a href="https://twitter.com/hashtag/iiif?src=hash&amp;ref_src=twsrc%5Etfw">#iiif</a> Presentation API 3.0 for a spin <a href="https://t.co/Eqn5SHYTXf">pic.twitter.com/Eqn5SHYTXf</a></p>&mdash; Jack Reed🐧 (@mejackreed) <a href="https://twitter.com/mejackreed/status/999849102807617536?ref_src=twsrc%5Etfw">May 25, 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">I think “IIIce IIIce Baby” is the official song of the <a href="https://twitter.com/hashtag/iiif?src=hash&amp;ref_src=twsrc%5Etfw">#iiif</a> karaoke community.</p>&mdash; Object-Oriented Pokémontology (@anarchivist) <a href="https://twitter.com/anarchivist/status/999839801712013312?ref_src=twsrc%5Etfw">May 25, 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

## IIIF Omnibus (IIIF for All)

The [IIIF Code of Conduct][conduct] states that "IIF is an inclusive, friendly and safe community, committed to openness and transparency in all interactions and activities."

 But we still have to do our best to reach out to minority groups and make them feel included.

 <blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">So happy that <a href="https://twitter.com/tcramer?ref_src=twsrc%5Etfw">@tcramer</a> said that diversity and inclusion is essential for the <a href="https://twitter.com/hashtag/iiif?src=hash&amp;ref_src=twsrc%5Etfw">#iiif</a> community in his closing remarks at the conference. Hoping we can keep that goal in mind for structural support at next year&#39;s conference.</p>&mdash; Object-Oriented Pokémontology (@anarchivist) <a href="https://twitter.com/anarchivist/status/1000113372380135424?ref_src=twsrc%5Etfw">May 25, 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

In order to spread the good word of IIIF, we need as a community to organise as many regional events as possible! 

<blockquote class="twitter-tweet" data-lang="en"><p lang="fr" dir="ltr">Conclusion de la conférence <a href="https://twitter.com/hashtag/IIIF?src=hash&amp;ref_src=twsrc%5Etfw">#IIIF</a> 2018 <a href="https://twitter.com/librarycongress?ref_src=twsrc%5Etfw">@librarycongress</a> par <a href="https://twitter.com/tcramer?ref_src=twsrc%5Etfw">@tcramer</a>, incitation à organiser des événements <a href="https://twitter.com/hashtag/IIIF?src=hash&amp;ref_src=twsrc%5Etfw">#IIIF</a> régionaux, à l&#39;image de <a href="https://twitter.com/biblissima?ref_src=twsrc%5Etfw">@biblissima</a> en mars dernier à Paris au <a href="https://twitter.com/CampusCondorcet?ref_src=twsrc%5Etfw">@CampusCondorcet</a> <a href="https://t.co/EST2mLeeYT">pic.twitter.com/EST2mLeeYT</a></p>&mdash; Régis Robineau (@regisrob) <a href="https://twitter.com/regisrob/status/1000058783320694786?ref_src=twsrc%5Etfw">May 25, 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

A IIIF Community Group for archives will probably come to life by the end of the year. Some information in the last IIIF newsletter: <http://iiif.io/news/2018/07/03/newsletter/>

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">There was a critical mass of interest in starting a <a href="https://twitter.com/hashtag/iiif?src=hash&amp;ref_src=twsrc%5Etfw">#iiif</a> community group focused on archives. <a href="https://twitter.com/anarchivist?ref_src=twsrc%5Etfw">@anarchivist</a> volunteered to convene an ad hoc discussion to explore group scope and charter; stay tuned and dial in!</p>&mdash; Tom Cramer (@tcramer) <a href="https://twitter.com/tcramer/status/999746656471060480?ref_src=twsrc%5Etfw">May 24, 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

To conclude, I would like to thank this fantastic community full of amazing people. But I would especially like to thank Glen Robson who does a wonderful job as the IIIF Technical Coordinator.

## Bonus: Strolling around Washington D.C.

When I discover a new place, I like to do it on foot and as a European, I always find that neat city street systems like grid plan or quadrant are fascinating, especially in North America, Australia, and let's be fair some European cities (such as Lisbon). Only in those cities would a walk with three street changes can take you about 50 minutes. :walking:

![DC Stroll][dc-stroll]

_Also, I recommend AXNO on Florida Avenue, they have great ciders._  

[notes-dc]: https://drive.google.com/drive/folders/1SsRYr7wQ5F3ZweoSjoAufcj20jKQkuxh
[conduct]: http://iiif.io/event/conduct/
[silos-to-iiif]: https://julsraemy.github.io/assets/images/silos_to_iiif.gif
[germani-medium]: https://medium.com/ecologiadigital/conhecendo-o-iiif-padr%C3%B5es-e-ferramentas-para-publica%C3%A7%C3%A3o-de-imagens-na-web-a62af62a1b36
[dcrain]: https://julsraemy.github.io/assets/videos/DCRain_Cramer.mov
[iiif-mdz]: https://www.digitale-sammlungen.de/index.html?c=iiif-info&l=de
[arodes-iiif]: http://arodes.hes-so.ch/record/2394
[comprendre-iiif]: https://insula.univ-lille3.fr/2016/11/comprendre-iiif-interoperabilite-bibliotheques-numeriques/
[iiif-biblissima]: http://doc.biblissima-condorcet.fr/introduction-iiif
[ressi-iiif]: http://www.ressi.ch/num18/article_142
[iiif-german]: https://drive.google.com/open?id=1PQAuaTbkPzmJOMDxtihyS0-gbUtTTcDC
[iiif]: http://iiif.io
[intro-iiif]: https://iiif.github.io/training/intro-to-iiif/
[intro-crane]: https://resources.digirati.com/iiif/an-introduction-to-iiif/ 
[2018iiif]: https://julsraemy.github.io/assets/images/2018iiif.png
[anno-usecases]: https://docs.google.com/document/d/16l2YoU4Portp5E89YEYMs_t0w48aBQut9Y0KjU-TnPs/edit
[dc-stroll]: https://julsraemy.github.io/assets/images/dc-stroll.png
[digirati]: https://digirati.com/
[digital-bod]: http://digital.bodleian.ox.ac.uk/
[matt-anno]: https://mattmcgrattan.github.io/Washington%20Annotation%20Workshop/
[mnemo]: http://mnemoscene.io/
[2018-iiif]: http://iiif.io/event/2018/washington/
[2018-monday]: http://iiif.io/event/2018/washington-workshops/
[2018-tuesday]: http://iiif.io/event/2018/washington/tuesday/
[2018-wed]: http://iiif.io/event/2018/washington/wednesday/
[2018-thursday]: http://iiif.io/event/2018/washington/thursday/
[2018-friday]: http://iiif.io/event/2018/washington/friday/
[2018-presentations]: https://drive.google.com/drive/u/0/folders/181NSHhuH1SiChi-xLA6sQyVQ9QNCNHb_
[ticks-rg]: https://www.researchgate.net/project/Towards-IIIF-Compliance-Knowledge-in-Switzerland-TICKS
[ticks-zenodo]: https://doi.org/10.5281/zenodo.1252083 
[canvas-panel]: https://canvas-panel.digirati.com/#/
[ronallo]: http://ronallo.com/
[ronallo-teaching]: https://ronallo.com/presentations/teaching-iiif-conf-2018/ 
[ronallo-awesome]: https://ronallo.com/presentations/awesome-iiif-conf-2018/
[ronallo-showcase]: https://ronallo.com/presentations/showcase-iiif-conf-2018/
[ronallo-workshop]: http://ronallo.com/iiif-workshop-new/
[awesome-iiif]: https://github.com/IIIF/awesome-iiif
[kzwa]: https://twitter.com/kzwa
[uv]: http://universalviewer.io/
[youtube-iiif]: https://www.youtube.com/channel/UClcQIkLdYra7ZnOmMJnC5OA
[wax]: http://marii.info/projects/wax
[crane-beyond]: https://medium.com/@tom.crane/beyond-the-viewer-fragments-and-links-in-annotation-space-b3284e25f34