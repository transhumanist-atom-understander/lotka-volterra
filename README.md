One of the core forms of explanation in the sciences is the dynamical model.
What I have in mind, more specifically, are systems of "ordinary differential equations".
We have some variables that vary over time, and for each one, we write how its time derivative depends on the other variables.

For example, there's the Lotka-Volterra model, with two variables: the size of a population of prey animals, and the size of a population of predators.
Instead of showing you the equations, I'll quote [Scott Alexander's summary of the dynamics](https://slatestarcodex.com/2020/05/12/studies-on-slack/):

> Every so often predators (let’s say foxes) reproduce too quickly and outstrip the available supply of prey (let’s say rabbits). There is a brief period of starvation as foxes can’t find any more rabbits and die _en masse_. This usually ends with a [boom-bust cycle](https://en.wikipedia.org/wiki/Lotka%E2%80%93Volterra_equations): after most foxes die, the rabbits (who reproduce very quickly and are now free of predation) have a population boom; now there are rabbits everywhere. Eventually the foxes catch up, eat all the new rabbits, and the cycle repeats again.

That's what it looks like in blog post style.
I think it's interesting to see because a lot of blog posts are similar in form, even if they're not summarizing a model from a quantitative science.
For example, let's say, [Scott Alexander's post on "respectability cascades"](https://slatestarcodex.com/2019/02/04/respectability-cascades/).

Scott actually presents two conflicting models of respectability cascades, with opposite predictions.
Should I say "models"?
I don't want to call these "dynamical models"; there's no system of ordinary differential equations, though I guess you could easily make one up.
I'll call them "dynamical explanations".

Among the many mechanistic explanations you see in blog posts, dynamical explanations are those in terms of quantities varying over time, and whether they increase or decrease depends on the other quantities.
The point of separately considering this kind of explanation is that we have this whole academic tradition of dynamical modeling available for formalizing them.

I also want to add that when a scientist proposes a dynamical model, it is often in a sense "just posting".
When Volterra proposed his predator-prey model, he was explaining the observation that even though World War I had given the fish a break from fishing, only the populations of predatory fish had increased, whereas the populations of prey fish had decreased.
A simple observation like that doesn't determine a mechanism, but it's still worth throwing the idea out there, which is the same as I would say of a lot of blog posts.

Bloggers don't turn their dynamical explanations into dynamical models.
Are they missing out?
Well, spoilers, not as far as I can tell, but for the rest of the post I'll consider what you get out of a dynamical model.

## Simulation

It's actually not obvious that Volterra's predator-prey model explains the observation he started with.
I suppose that's what applied math is for: when you've made assumptions with non-obvious implications.

Volterra had to do derivations on paper.
These days we have it easier, and can just simulate.
In principle we've had it easier since the creation of the personal computer, I suppose.
But in the days before coding agents, I rarely simulated anything that wasn't for school or work.
But now, why not?

But returning to Scott Alexander's respectability cascades, what's there to simulate?
At low initial levels of respectability, one model assumes a few disreputable advocates hurt the cause, so low respectability is stable.
The other assumes disreputable advocates bring in reputable ones, so we have a takeoff.
I could plot one curve going down to zero and another going up, but what's the point?
We don't seem to be interested in a non-obvious behavior.

## Comparison to data

Another thing people do with dynamical models is compare predictions to data.
I guess we could do that with dynamical explanations in blog posts, but with what data?
For example, in the respectability cascades post, while we have surveys about the respectability of homosexuality in each year, I don't see how you'd quantify the number of advocates of different levels of respectability.
For another topic he considers, the disrespectability cascade around endocrine disruptors, we would lack even survey data on the respectability of the topic.

There's a better prospect for comparing to data in a more recent post Scott wrote on something like disrespectability cascades.
That was "[Give Up Seventy Percent Of The Way Through The Hyperstitious Slur Cascade](https://www.astralcodexten.com/p/give-up-seventy-percent-of-the-way)".
It's about word use, and frequency of word use by a publication is easy to quantify.

The point, I guess, would be to notice when a superficial resemblance doesn't hold up.
For example, the classic dataset for illustrating Lotka-Volterra starvation cycles is [the Hudson's Bay Company dataset](https://www.mun.ca/biology/scarr/Hudson_Bay_population_cycles.htm) quantifying how many lynx and hare pelts they bought from trappers over almost a hundred years:

![](https://res.cloudinary.com/lesswrong-2-0/image/upload/v1794625242/lexical_client_uploads/whmb4jibqm5yyqttpcjw.gif)

It seems to show clear cycles, but on closer inspection, it seems that sometimes lynx populations crash first.
An early attempt to fit a generalization of the Lotka-Volterra model to the data resulted in [the paper "Do hares eat lynx?"](https://doi.org/10.1086/282870).

But is that important?
Canadian lynx and hares probably do go through Lotka-Volterra starvation cycles.
We see them in modern data, for example, [figure 13.1 in this book chapter on the Kluane Project](https://www.zoology.ubc.ca/~krebs/downloads/Kluane%20Book%20-%20Ch13%20-%20Coyotes%20and%20Lynx.pdf), with the caveat that this also reflects animals leaving the study area:

![](https://res.cloudinary.com/lesswrong-2-0/image/upload/v1794625195/lexical_client_uploads/kexhe3t6l6kdnub9rofz.png)

I'm not sure what's up with the pelt data.
[One idea](https://doi.org/10.1007/s10441-018-9333-z) is that there was also cyclical trapping activity, undermining the assumption that pelt counts measure populations.
But I'm sure any casual attempt to quantify the variables discussed in a blog post would run into even worse issues with whatever you use as a proxy for the variable of interest.

## Conclusion

My background is in mathematical biology.
It's interesting because you learn to propose poorly motivated models you can't really test, just like the economists, but unlike economics it isn't politicized.

There's certainly an art to this kind of thing, which I think I've learned to some extent.
It's interesting to see that much of the blogosphere is in a sense within the domain of that art.
But maybe the main thing I've learned is just how hard it is, beyond the resources you'd be willing to put into a blog post.
Though it's easier than it used to be, with simulation and data analysis software, and coding agents to run it for you.

The optimistic spin, I suppose, is that I can see the continuity, the spectrum from just posting to settled science.
You propose multiple alternative hypotheses, you derive their consequences, you compare them to data and see which survive.
The more of that effort you make, the more you know.
Blogosphere ideas aren't impermissible unscientific speculation, just low-effort.
