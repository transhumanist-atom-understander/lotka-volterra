Insight porn should not be taken too seriously.
And I think the key to taking it lightly is that to remember that stories like these are cheap.
I mean, stories that fit the facts to the standard of a blog post are cheap.
Of course in the moment I always get caught up in the story, but afterwards, I learn of or think of other explanations, and by now I've come to expect it.

Actually, this isn't really just about blog posts.
The same principle applies when a professor publishes a paper, with an explanation in the language of differential equations.
When Volterra proposed the Lotka-Volterra model in ecology, he didn't have a mountain of data to pin it down, but rather, just the observation that fish populations didn't rebound when fishing was interrupted by World War I.

I think the Lotka-Volterra model is a good case study in how a compelling mechanism is really just one of many possible stories.
Let's get it in blog post style, [from Scott Alexander](https://slatestarcodex.com/2020/05/12/studies-on-slack/):

> Every so often predators (let’s say foxes) reproduce too quickly and outstrip the available supply of prey (let’s say rabbits). There is a brief period of starvation as foxes can’t find any more rabbits and die en masse. This usually ends with a [boom-bust cycle](https://en.wikipedia.org/wiki/Lotka%E2%80%93Volterra_equations): after most foxes die, the rabbits (who reproduce very quickly and are now free of predation) have a population boom; now there are rabbits everywhere. Eventually the foxes catch up, eat all the new rabbits, and the cycle repeats again.

In this post I'm going to try and take you through a different kind of cycle, from being enraptured by an insight to seeing it as just one in an ensemble of possibilities.
Not that we're going to refute this kind of starvation cycle; it's a general mechanism, and presumably happens somewhere.
Rather, I'm going to walk through a few examples of ecosystems, and hopefully communicate the feeling that this is obviously what's going on, before raising other possibilities.

In fact, I'll start with the standard examples from the Wikipedia article on the Lotka-Volterra model (linked in the previous quote).
It says:

> Fluctuating numbers of predators and prey have been observed in natural populations, such as the lynx and snowshoe hare data of the Hudson's Bay Company and the moose and wolf populations in Isle Royale National Park.

Let's take a look.

## Hudson's Bay Company lynx and hares

![](https://www.mun.ca/biology/scarr/Lynx-Hare_cycle.gif)

([Image source](https://www.mun.ca/biology/scarr/Hudson_Bay_population_cycles.htm))

Beautiful cycles, though maybe the dates ring alarm bills.
Was there really a long running ecological population study in the 19th century?

Actually these are not counts of populations, they are counts of pelts.
Hudson's Bay Company was in the fur business.
The traditional interpretation is that it's a proxy for population, like trappers are sampling animals.

What do we see.
In 1845, lynx populations are high, but there's not many hares.
Lynx populations crash, we suppose due to starvation, and hares reproduce wildly.
Lynx population grows, then... plumments, not clearly before the hare population?

Many of the cycles go how we expect, with the hare population dropping when the lynx population is high, then the lynx population following.
But some of them do not; the lynx population seems like it may be crashing simultaneously or even first.

It's pretty hard to judge from a plot like this.
We can see it more clearly, watching in phase space:

When the clock turn backwards, that's the population crashes coming in the wrong order.

This was first pointed out in [a paper titled "Do hares eat lynx?"](https://doi.org/10.1086/282870)
Well, that's not the most plausible explanation.
Here's one that I liked but haven't really judged: these cycles are actually cycles of trapping activity.
Trappers work other gigs when populations are depleted and return when they recover.
They preferentially target lynx for their more valuable pelts, explaining why lynx populations sometimes crash first.

If that's true, there should be some record of it, but interpreting the data has turned into a historical problem.
The good, clean data is modern data from national parks, which is what we'll look at next.
