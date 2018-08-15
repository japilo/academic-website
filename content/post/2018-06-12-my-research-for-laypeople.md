+++
title = "My current research, for laypeople"
date = 2018-06-12T00:00:00
tags = ["research summary", "colorednoise"]
+++

I have struggled a lot to explain my current line of research to people in my life who aren't scientists. But if I can't explain my research to everyone, then I can't claim to really know what I'm doing. So I'm going to try my best.

Models of natural phenomena – say, the size of the elephant population in a nature reserve – usually have some kind of randomness in them, because natural systems constantly change. Randomness is usually modeled as *white noise*, like this:

![white noise](/posts/white noise.png)

The problem is that randomness in natural phenomena is usually not white noise, but *colored noise*. See, the randomness of white noise has no "memory." Each point is uncorrelated to the point that came before it. But that's not how it works in the real world.
If the water level in a lake is high this year, it's more likely to be high next year. The water level is still fundamentally random, but conditions tend to carry over from year to year. This kind of randomness is called *red noise.*

![red noise](/posts/red noise.png)

The other type of colored noise is *blue noise*. With blue noise, each point tends to go in the opposite direction of the one before it. This is like masting in trees, where they tend to make a lot of pollen and a lot of flowers one year and much less the next.

![blue noise](/posts/blue noise.png)

When you look at randomness in natural phenomena, like the number of elephants in a nature reserve or the water level of a lake or sea surface temperatures in the North Atlantic, they tend to have red noise. If you want to make a model of a natural system that
includes randomness, it's more realistic if you model that randomness as red noise. Now, a realistic model is not always the best model. Sometimes a simple model is better if it does a good job describing the natural system using less information. But I wanted to
know whether a particular type of population model – a model of how an animal or plant population grows and declines over time – is improved by using colored noise instead of white noise.

To do that, I made a open source software package in the programming language R called [colorednoise](http://cran.r-project.org/package=colorednoise). This package can create colored noise and run population models with colored noise. I've been using the package
on plant and animal population data from the [COMPADRE and COMADRE databases](http://www.compadre-db.org/), which make these data publicly available for scientists to use in ecological research. I've finished the study already, it's just a matter of writing it up
into a scientific article at this point!
