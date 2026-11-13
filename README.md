One of the core forms of explanation in the sciences are dynamical models.
What I have in mind, more specifically, are systems of "ordinary differential equations".
We have some variables that vary over time, and for each one, we write how its time derivative depends on the other variables.

For example, there's the Lotka-Volterra model, with two variables: the size of a population of prey animals, and the size of a population of predators.
Instead of showing you the equations, I'll quote [Scott Alexander's summary of the dynamics](https://slatestarcodex.com/2020/05/12/studies-on-slack/):

> Every so often predators (let’s say foxes) reproduce too quickly and outstrip the available supply of prey (let’s say rabbits). There is a brief period of starvation as foxes can’t find any more rabbits and die en masse. This usually ends with a [boom-bust cycle](https://en.wikipedia.org/wiki/Lotka%E2%80%93Volterra_equations): after most foxes die, the rabbits (who reproduce very quickly and are now free of predation) have a population boom; now there are rabbits everywhere. Eventually the foxes catch up, eat all the new rabbits, and the cycle repeats again.

That's what it looks like in blog post style.
I think it's interesting to see because a lot of blog posts are similar in form, even if they're not summarizing a model from a quantitative science.
For example, let's say, [Scott Alexander's post on "respectability cascades"](https://slatestarcodex.com/2019/02/04/respectability-cascades/).

Scott actually presents two conflicting models of respectability cascades, with opposite predictions.
Should I say "models"?
I don't want to call these "dynamical models", there's no system of ordinary differential equations, though I guess you could easily make one up.
I'll call them "dynamical explanations".

Dynamical explanations are just one kind of explanation you find in blog posts.
Which is interesting about them to me is that we have this whole academic tradition of dynamical modeling, for handling similar sorts of explanations.

I also want to add that when a scientist proposes a dynamical model, it is often in a sense "just posting".
In a way I'm blessed to have a background in mathematical biology.
You learn to propose bullshit models like the economists do, but it's not so political.
When Volterra proposed his predator-prey model,

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
