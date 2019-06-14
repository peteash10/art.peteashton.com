---
layout: post
title: Instabeck
description: Imagining a lost sculpture using Instagram images
image: /assets/images/Instabeck-1024x896.png
permalink: instabeck
categories:
  - Gallery
  - Commission
  - Visual Art
---

![](/assets/images/Instabeck-1024x896.png)

# InstaBeck 

*by [Pete Ashton](http://peteashton.com)*

![](https://raw.githubusercontent.com/peteash10/Artworks/master/images/Instabeck-1024x896.png)

I was delighted to be chosen by [Jo Gane](http://jogane.co.uk/) to exhibit at [The JHB Archive](http://www.bom.org.uk/event/the-jhb-archive/), her group show at Birmingham Open Media running from Sept 11th to Oct 3rd 2015.

All the pieces are inspired by the scant information on [the archival record for a missing sculpture](https://github.com/peteash10/Artworks/blob/master/Instabeck/Submission%20brief.pdf), reverse-engineering the metadata into art, if you like.

My piece continues work taking core samples of photographic images from social sharing networks which I first developed with the **IMG_4228** series. I started with the text of the archive record itself which I split into 7 lines of 8 words each.

`abstract sculpture by julian h beck rectangular mahogany`

`type walnut according to sculptor marked 25 in`

`paint near base two roundhead screws for attachment`

`to plinth on regtangular plinth covered in black`

`tape inside of plinth marked 23 1961 or`

`28 1961 number painted out and replaced by`

`new number see press cuttings file and minutes`

![](https://raw.githubusercontent.com/peteash10/Artworks/master/images/InstaBeck%200.jpg)

I put each word / letter / number into Instagram as a hashtag and saved the first eight images that came up. I then put these into a couple of grids.

![](https://raw.githubusercontent.com/peteash10/Artworks/master/images/InstaBeck%201.jpg)

![](https://raw.githubusercontent.com/peteash10/Artworks/master/images/InstaBeck%202.jpg)

Unsatisfied with how these looked, I cropped each image to its central pixel (finding the average colour simply produces a lot of grey/brown) and resized them back up to 200x200px, giving a nice clean field of colour.

The final stage was to randomise the image. For this I used [PureData](https://puredata.info/), writing [the following patch](https://github.com/peteash10/Artworks/blob/master/Instabeck/Installation%20code%20and%20images/instabeck.pd).

[![](https://raw.githubusercontent.com/peteash10/Artworks/master/images/Instabeck%20PD%20patch.png)](https://github.com/peteash10/Artworks/blob/master/Instabeck/Installation%20code%20and%20images/instabeck.pd)

Which no doubt looks terrifying, but it’s actually pretty simple. Each of these…

![](https://raw.githubusercontent.com/peteash10/Artworks/master/images/instabeck-patch-zoom.png)

…builds a square representing a word/letter/number from the description, and all the lines coming into that bit randomises which colour is shown.

To pre-load the work you hit the orange button, then the green button launches the video changing a square every second, though the speed can be changed using the blue buttons.

Over in the top-right is an optional bit of code which uses the computer’s microphone to alter the speed, so a noisy room will produce a frenetic display while silence will freeze it.

[Here's a video](https://vimeo.com/138805236) of it is in situ during testing:

[![](https://raw.githubusercontent.com/peteash10/Artworks/master/images/Instabeck%20Vimeo.jpeg)](https://vimeo.com/138805236)

But for most of the exhibition a pre-recorded loop can run to save electricity.

By a happy co-incidence the work bears a striking similarity to one of Beck’s own paintings and Jo sent me a photo.

![photo](https://raw.githubusercontent.com/peteash10/Artworks/master/images/Instabeck%20Beck%20Painting.jpg)

Nice!


