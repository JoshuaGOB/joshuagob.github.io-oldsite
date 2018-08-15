---
layout: single
title: "Mallet, Programming Historian, Tesseract y ScanTailor"
date: "2018-08-14"
share: true
permalink: "/_posts/2018-08-14-mallet-programming-historian-tesseract-scantailor"
categories: 
 - Academia
 - Universidad
classes: wide
---

I have a pending task of finding a way of generating a multilingual site. The theme for this jekyll page has the ui text included but I think there are more steps involved in order to do a switchable site.

***

The Mellon grant that funds my position has a requirement of three workshops that use the materials for which they disembursed funds. The first one is scheduled for September 26 and will probably be led by Jennifer Isasi. At the moment, we're considering using topic modelling, Mallet seems to be the likely candidate, and the Cirma newspapers that I've been processing for the last four months. I wanted to try out writing bash scripts and automating some of the process involved in Tesseract, so I had been playing with the images on and off. There's a lot of issues from a technical standpoint. The images are cutouts of the articles, which makes life easier, but there is identifying information on the sheets of paper that hold each article. Sometimes there are two small articles on one sheet and a sort of categorization on the page. This tripped up Tesseract pretty badly. I started playing around with Scantailor to see if the process of cropping and content selection could be done quicker, it allows you to sort the images by width or height and that's super useful for batch processing. I wanted to have a test data set to then move on to OCR ground truth software since I had originally had a conversation with Hannah Alpert-Abrams at the beginning of the year on this very topic. Other stuff came up and I decided to hurry part of the process of editing the images. The corpus is there and with some time spent editing the images it could be relatively clean thanks to the fact that the images are mainly single articles and there are no columns to confuse Tesseract.

***

As part of the Mellon requirements, we also have to create a guide in Spanish for the tool and research method employed. Turns out that Jennifer is a member of the editorial board of the Programming Historian. They've been making a big push to include multilingual guides and this seems like the perfect opportunity. The Mallet guide they have now is a bit old, even though it works well still, and it could do even better with more information and more details about theory and results. I have the impression that the tutorials have to be kept relatively simple, it's a tutorial and not a class, but it's super exciting to think that something that has given me so many headaches could be of use to others. I want to find a way to start drafting that document straight away, as I'm scanning the manuscripts for Kelly McDonough's undergraduate course, OCRing the rest of the documents, translating the texts for the post-custodial team, processing the Primeros Libros from Biblioteca Nacional de México and whatever teaching support I need to do for Lina del Castillo's class. 

I'm hoping to have a clean copy of the Tesseract tutorial. It really doesn't lend itself to a visual guide and neither does Mallet but I think that's the preferred method.  
