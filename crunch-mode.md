---
layout: page
title: "Crunch Mode"
---

I used to brag about the hours I was working.
Not in so many words, of course---I had *some* social skills.
Instead, I'd show up for work around noon,
unshaven and yawning,
and casually mention how I'd been up 'til 6:00 a.m.
hacking away at some monster bug.

Looking back, I can't remember who I was trying to impress.
Instead,
what I remember is how much of the code I wrote in those all-nighters
I threw away once I'd had some sleep,
and how much damage the bugs I created in those bleary-eyed stupors did to my teammates' productivity.

My mistake was to confuse "working" with "being productive".
You can't produce software (or anything else) without doing some work,
but you can easily do lots of work without producing anything of value.
Scientific study of the issue goes back to at least the 1890s---see [[Robinson2005](../references/#Robinson2005)]
for a short, readable summary.
The most important results for developers are:

1.  Working more than eight hours a day for an extended period of time lowers your total productivity,
    not just your hourly productivity---i.e.,
    you get less done in total (not just per hour)
    when you're in crunch mode than you do when you work regular hours.

1.  Working over 21 hours in a stretch increases the odds of you making a catastrophic error
    just as much as being legally drunk.

These facts have been reproduced and verified through hundreds of experiments
over the course of more than a century.
The data behind them is as solid as the data linking smoking to lung cancer.
However,
while most smokers will admit that their habit is killing them,
people in the software industry still talk and act as if they were somehow exempt from these findings.
To quote Robinson's article:

> When Henry Ford famously adopted a 40-hour workweek in 1926,
> he was bitterly criticized by members of the National Association of Manufacturers.
> But his experiments,
> which he'd been conducting for at least 12 years,
> showed him clearly that cutting the workday from ten hours to eight hours---and
> the workweek from six days to five days---increased total worker output and reduced production cost...
> the core of his argument was that reduced shift length meant more output.
>
> ...many studies, conducted by businesses, universities, industry associations and the military,
> ...support the basic notion that, for most people,
> eight hours a day, five days per week, is the best sustainable long-term balance point
> between output and exhaustion.
> Throughout the 30s, 40s, and 50s, these studies were apparently conducted by the hundreds;
> and by the 1960s,
> the benefits of the 40-hour week were accepted almost beyond question in corporate America.
> In 1962,
> the Chamber of Commerce even published a pamphlet extolling the productivity gains of reduced hours.
>
> But, somehow, Silicon Valley didn't get the memo...

I was part of a data visualization startup in the mid-1990s.
Three months before our first release,
the head of development "asked" us to start coming in on Saturdays.
We were already pulling one late night a week at that point
(without overtime pay---our bosses seemed to think that
ten dollars' worth of pizza was adequate compensation for four hours of work)
and most of us were also working at least a couple of hours at home in the evenings.
It's hardly surprising that we missed our "can't miss" deadline by ten weeks,
and had to follow up our 1.0 release with a 1.1,
and then a 1.2,
in order to patch the crash-and-lose-data bugs we'd created.
We were all zombies,
and zombies can't code.

Those kinds of hours are sadly still normal in many parts of the software industry.
Everyone knows that designing and building software is a creative act that requires a clear head,
but many of those same people then act as if it was like digging a ditch.

The big difference is that it's hard to lose ground when digging (though not impossible).
In software,
on the other hand,
it's very easy to go backward.
It only takes me a couple of minutes to create a bug
that will take hours to track down later---or days,
if someone else is unlucky enough to have to track it down.
This is summarized in Robinson's first rule:

> Productivity varies over the course of the workday,
> with the greatest productivity occurring in the first four to six hours.
> After enough hours,
> productivity approaches zero;
> eventually it becomes negative.

It's hard to quantify the productivity of programmers, testers, and UI designers,
but five eight-hour days per week has been proven to maximize long-term total output
in every industry that has ever been studied.
There's no reason to believe that software development is any different,
or that student programming is different from full-time programming in industry.

Ah, you say, that's "long-term total output".
What about short bursts now and then,
like pulling an all-nighter to meet a deadline?
That's been studied too, and the results aren't pleasant.
Your ability to think drops by 25% for each 24 hours you're awake.
Put it another way,
the average person's IQ is only 75 after one all-nighter,
which puts them in the bottom 5% of the population.
Two all nighters in a row and their effective IQ is 50---the level at which
people are usually judged incapable of independent living.

The catch in all of this is that people usually don't notice their abilities declining.
Just like drunks who think they're still able to drive,
people who are deprived of sleep don't realize that they're not finishing their sentences (or thoughts).
They certainly don't realize that they're passing parameters into function calls the wrong way around,
or that what they're typing in will all have to be deleted and re-done tomorrow,
when it will take longer than it would have if they'd just gone home and gotten a good night's sleep.

The moral of this story?
Think very hard about what's more important to you:
the amount of good work you produce,
or how much of a martyr you appear to be.
Then think about which of those other people are actually going to care about
and pace yourself accordingly.

{% include links.md %}
