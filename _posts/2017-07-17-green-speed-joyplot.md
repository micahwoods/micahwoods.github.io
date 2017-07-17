---
layout: post
title: "Green speed joyplot and the work to produce these conditions"
subtitle: More about the ease of producing green speeds by species
share-img: "http://www.asianturfgrass.com/img/poa_green.jpg"
tags: [green speed, mowing, fertilizer]
bigimg:
- "/img/serangoon_green.jpg"    : "serangoongrass green, Singapore"
- "/img/poa_green.jpg"          : "Poa annua green, California"
- "/img/topdress_eagle.jpg"     : "bermudagrass green, Thailand"
- "/img/korai_stimpmeter.jpg"   : "korai green speed measurement, Fukuoka"
---

First, here are data from 867 measurements I've made from 2011 to 2016 excluding all tournament measurements. 

Table 1: Number of measurements and median green speed in feet, by species. Data from 867 stimpmeter readings by Micah Woods excluding tournament measurements.

| species   |    n|  median|
|:----------|----:|-------:|
| bent      |  270|     9.0|
| bent-poa  |   18|    11.0|
| bermuda   |  308|     8.9|
| fescue    |   15|     8.8|
| korai     |   72|     7.7|
| paspalum  |  141|     8.3|
| poa       |   19|    10.1|
| serangoon |   24|     7.1|

This shows those green speed data summarized in the form of a [joyplot](https://cran.rstudio.com/web/packages/ggjoy/vignettes/introduction.html).

![joyplot of green speed measurements by grass species](/img/joy_speed.svg)

[I suggested yesterday](http://www.asianturfgrass.com/2017-07-16-species-ease-speed/) that I expect the amount of work required to produce the same speed for all the grasses (given mid-growing season conditions in a location where the grass is well-adapted) will be the greatest for zoysiagrass and the lowest for fine fescue.

I adapted the chart from yesterday with data I've collected on green speed of these grasses.

![green speed medians by grass species](/img/ease_with_speed.svg)

One could draw a line on the chart from bent-poa to *Poa annua*, bermudagrass, seashore paspalum, and ending at zoysiagrass, and it would match my prediction exactly, if the amount of work done to those surfaces on average was the same. 

You'll notice of course that fine fescue, bentgrass, and serangoongrass are *not* on that line that one could draw from bent-poa to zoysiagrass. And I have a good explanation for this. For the fine fescue and serangoongrass, I'm confident that the average maintenance work done at the courses I collected data from was much less than at the other courses. If equivalent work was done, I expect the green speed from those grasses would jump right up to that line.

For example, [this video](https://youtu.be/tqWjV3qvoQ0) is one of the courses with serangoongrass. They call it bluegrass in the video.

<iframe width="560" height="315" src="https://www.youtube.com/embed/tqWjV3qvoQ0" frameborder="0" allowfullscreen></iframe>

And for the bentgrass, a lot of the measurements were made in Japan in summer. The temperatures there in summer are something in-between Jacksonville and Atlanta -- see [this post](http://www.blog.asianturfgrass.com/2015/01/when-is-it-too-hot-to-grow-bentgrass-a-look-at-nighttime-lows-above-x-y-and-z.html) on when it's too hot to grow bentgrass -- so the median value for the bentgrass is a bit low because this is not a location where the grass is well-adapted.

There were some comments about fine fescue being softer than Poa, or not. I may very well be wrong about that. I'm mixing up my thinking about the amount of work required, and also the way the ball is going to roll across or through a leaf surface of the different species. 

The way I think of it is this. Let's imagine a fescue green mown at 5 mm, mown 4x per week, rolled 2x per week, with no fungicides applied, 5 g N m<sup>-2</sup> year<sup>-1</sup>, a bit of sand topdressing, no growth regulators, and irrigation to prevent dormancy. Do that same amount of work to *Poa annua*, and I predict the green speed will be faster on fescue than on *Poa*. Also, the *Poa* is probably going to be disease-infested and horrid with that amount of work, so to achieve the same conditions with *Poa* it is apparent that more work is required. 

Now do the same to zoysiagrass. I'm sure a mid-season zoysia green mown 4x weekly at 5 mm will have a green speed about 5 or 6. In this case I've measured greens maintained something like that. And I predict fescue again is going to have a faster speed than zoysia given that type of maintenance work. Maybe a better way for me to explain what I'm thinking, rather than saying rigidity or softness of the leaf, would be for me to express this as resistance to roll. The fescue I think is going to offer the least resistance, and the *Poa* more, and the zoysiagrass the most.

And for even more about these type of data, please read my [Report on Putting Green Performance Characteristics](http://www.files.asianturfgrass.com/20120802_data_report.pdf).
