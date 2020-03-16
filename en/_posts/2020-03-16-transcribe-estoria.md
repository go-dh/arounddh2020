---
layout: project
lang: en
lang-ref: transcribe-estoria
ref: transcribe-estoria
title: "TranscribeEstoria"
author: "Polly Duxfield and Aengus Ward"
description: "A crowdsourced transcription pilot project for Estoria de Espanna"
permalink: /en/transcribe-estoria
image: true
include: false
---
### About the project
[TranscribeEstoria](https://transcribeestoria.bham.ac.uk/en/) was a proof-of-concept pilot project that ran from September to December 2019. The pilot included palaeography and transcription training for non-specialist volunteers, using online teaching materials and methods, followed by a series of five short passages for transcription, which launched once per fortnight for ten weeks. Alongside the passages we released a series of topical [blog posts](https://blog.bham.ac.uk/estoriadigital/blog/) to deepen and widen the learning experience for transcribers.


### What are the stakes?
The objective was to ascertain whether there was a crowd willing to do transcription, and to test our transcription platform. The application is available in both English and Spanish, and allows users (including those outside academia) to independently register as a transcriber, learn how to use the interface with training videos and PDF guides, practice with a sample text, and then transcribe from illuminated manuscripts released weekly. The project was designed to offer an intuitive interface with a zoomable pane that allows the viewer to focus on the specific part of the manuscript they were looking at as they went along, and giving them the ability to save their progress and return at a later point, with the transcription being stored behind the scenes in TEI XML. The tool also provided researchers who had an admin role to upload images and manuscript text and gave them the ability to view and sort the recorded data from the transcribers. Features such as expandable special characters, medieval punctuation, decorative features such as rubrication, coloured or larger initials, the option to mark where text was missing / illegible and other marginalia made this tool particularly useful to transcribers and the researcher. 

The eventual aim of TranscribeEstoria is to use crowdsourced transcriptions to add witnesses of the Estoria de Espanna to [our edition of this work, version 1.0 of which launched in 2016](http://estoria.bham.ac.uk/edition/). This project fits within the wider [Estoria de Espanna Digital project](https://www.dhi.ac.uk/estoria), which has the objective of widening public understanding of and access to medieval materials which are fundamental to the cultural and linguistic heritage of Spain.


### What have you learned doing this project?
The pilot project allowed us to road-test our pedagogical approach and our transcription platform, both of which evolved throughout the course of the project. We learnt about the optimal timings between passage launches, and were reminded of the scepticism with which crowdsourced transcription projects can be viewed within Spain in particular, and we considered methods to mitigate against this where possible. We also didn’t learn, but had reinforced for us, the extent to which the transcription of medieval manuscripts can be addictive, and both frustrating and hugely rewarding.



### Tools
We used Django, Python, HTML, CSS, Javascript / JQuery, and Bootstrap to develop the transcription platform.


### Source material
The passages were from manuscript C of the [Estoria de Espanna](https://en.wikipedia.org/wiki/Estoria_de_Espa%C3%B1a) (Biblioteca Nacional de España, MS 12837). The materials for transcription are written in fourteenth-century Castilian, but training materials and blogs were available in both English and Spanish.


### Collaborators
The TranscribeEstoria team consisted of Prof Aengus Ward (University of Birmingham, but a proud Dubliner), Dr Ricardo Pichel (Universidad de Alcalá and Universidade de Santiago de Compostela), and Dr Polly Duxfield (University of Birmingham). We collaborated with scholars from the Research Software Group in the Advanced Research Computing Team at the University of Birmingham, and much of the coding was carried out by Cerys Lewis. This team helped to develop the main tool we used in this project: our new transcription platform with WYSIWYG (what you see is what you get) buttons to input a range of TEI5-compliant XML tags. Volunteer transcribers were from a range of countries, including the UK, Spain, Brazil and Argentina.


*Image credit: Biblioteca Nacional de España*
