---
title: Schematic finalized
description: Status report of the OpenSX70 project as of November 2017
date: 2017-11-10T00:00:00.000Z
layout: post
author_name: Joaquín de Prada
author_url: /author/joaquin
author_avatar: joaquin
show_avatar: true
read_time: 34
feature_image: SX70_images/openSX70-cameraporn-9
show_related_posts: false
square_related: recommend-wolf
permalink: /posts/2017/11/report/
comments: true
categories: openSX70
published: true
---

I am getting quite confident with EagleCAD and have "finalized" the schematic. I has been amazing learning to use the program. 
I have also been testing the light meter chip, BH1750, it is really really small, and I only had a big adapter board. It works but it has been a struggle. I wonder if it will be fast enough to know "on the fly" the exposure once the shutter opens.

I have also been testing the shutter with the SMD N-mosfet (AO3400) and PWM "power down" mode. I took this footage with the iPhone in slow motion.

{% include video id="yd0hI180bVs" provider="youtube" class="full"%}

I have also decided to use limiter resistor to lower the current in S9 and S8, since I have decided to use the Atmega at 3.3v to reduce power consumption. I have also decided to use a 16mhz crystal for timing stability. By the way the slow motion footage the delay is set for 45ms. I have to test how fast I can shoot realistically.

I hope to be able to manufacture some test boards soon…

![Fire image]({{site.url}}/{{site.baseurl}}img/20171105/1.jpeg)
![Fire image]({{site.url}}/{{site.baseurl}}img/20171105/2.jpeg)
![Fire image]({{site.url}}/{{site.baseurl}}img/20171105/3.jpeg)
![Fire image]({{site.url}}/{{site.baseurl}}img/20171105/4.jpeg)
