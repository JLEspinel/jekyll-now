---
published: true
---
This post is dedicated to all you lucid dreamers. It's the convergent evolution of three recent encounters with one question: what are the computational limits of the human brain?

## Encounter 1:

I first started thinking about this while reading an entirely unrelated essay from [Rationality: AI to Zombies](https://www.readthesequences.com/). In Book 2, Yudkowski makes the following statement:

> Unsurprisingly, the human brain doesn’t do 64-bit floating-point arithmetic, and it can’t devalue the emotional force of a pleasant anticipation by a factor of 0.00000001 without dropping the line of reasoning entirely.

When read in context, it's found in a section that really has nothing to do with computational limits (it's an esssay on lotteries, of all things). But my mind started to wander, and it stuck with me. If the brain doesn't do "64-bit floating point arithmetic"... then what _can_ it do?

And how fast can it do it (_it_ being some sort of basic, singular mental computation)?

An interesting thought, but other things came up that day and I let it go.

## Encounter 2:

These two questions were narrowed down a few days later. I was talking about lucid dreaming with a friend (Lucas Rosen). More specifically, we were talking about the brain's remarkable ability to conjure up entire personalities and landscapes seemingly on command while we dream. 

Remembering the thought I had while reading Yudkowski, I stopping the marveling and sketched out the following scenario for Lucas:

Imagine you're in a lucid dream.

You're suspended 5,000 feet above an endless city, laid upon an endless plane (we'll say it's a flat-earth version of an ecumenopolis like Coruscant).

Your only option is to fly forward, but you can vary the speed at which you do so.

We assume that your dream runs in real-time, or if not, that at least mental computations occur at fixed intervals.

If you started moving forward, ever accelerating, would you ever reach a point where your mind can't keep up computationally, and starts "lagging" or "dropping frames"?

We were intrigued.

## Encounter 3:

Before I even had the chance to read into anything on the brain's computational limits I ran into the topic one final time, this time in [an SSC post on DMT entities](http://slatestarcodex.com/2015/04/21/universal-love-said-the-cactus-person/):

> “Universal love,” said the cactus person.
“Transcendent joy,” said the big green bat.
“Right,” I said. “I’m absolutely in favor of both those things. But before we go any further, could you tell me the two prime factors of 1,522,605,027, 922,533,360, 535,618,378, 132,637,429, 718,068,114, 961,380,688, 657,908,494, 580,122,963, 258,952,897, 654,000,350, 692,006,139?

Check out the SSC post for context. What matters for this post is that it riled me up again. What _could_ we factor in a dream?

So, at the end of the week I was left with this burning, unanswered question about how complex our dreams can get. At that point I set about trying to amass enough literature on the subject that I might get a general idea of whether those limits exist, and if they do where the qualitative/quantitative boundaries lie. One strategy for making sense of the unknown is to relate it to a well-understood analogue. In the case of the brain, we can, as many have, relate it to a Turing machine (the stance known as the ["classical computational theory of mind"](http://www.iep.utm.edu/compmind/#SH1a)). But this comparison has several shortcomings. Stanford's Encyclopedia of Philosophy lays them out rather clearly:

> Turing machines execute pure symbolic computation. The inputs and outputs are symbols inscribed in memory locations. In contrast, the mind receives sensory input (e.g., retinal stimulations) and produces motor output (e.g., muscle activations). A complete theory must describe how mental computation interfaces with sensory inputs and motor outputs.

> A Turing machine has infinite discrete memory capacity. Ordinary biological systems have finite memory capacity. A plausible psychological model must replace the infinite memory store with a large but finite memory store

> Modern computers have random access memory: addressable memory locations that the central processor can directly access. Turing machine memory is not addressable. The central processor can access a location only by sequentially accessing intermediate locations. Computation without addressable memory is hopelessly inefficient. For that reason, C.R. Gallistel and Adam King (2009) argue that addressable memory gives a better model of the mind than non-addressable memory.

> A Turing machine has a central processor that operates serially, executing one instruction at a time. Other computational formalisms relax this assumption, allowing multiple processing units that operate in parallel. Classical computationalists can allow parallel computations (Fodor and Pylyshyn 1988; Gallistel and King 2009: 174). See Gandy (1980) and Sieg (2009) for general mathematical treatments that encompass both serial and parallel computation.

> Turing computation is deterministic: total computational state determines subsequent computational state. One might instead allow stochastic computations. In a stochastic model, current state does not dictate a unique next state. Rather, there is a certain probability that the machine will transition from one state to another.

So the mind is less like a Turing machine... and more like a modern computer. It has finite memory (read: limit #1, and that memory includes some RAM- or VRAM-esque component, we'll get to that division soon) and computations are executed in a nonzero amount of time (read: limit #2). I also want to use the assumption that the brain is able to run an enormous amount of computations in parallel. Although academically this remains a moot point, the rationale behind it makes sense: neurons are surprisingly slow at passing along information. They're not just slow - they're slower than man-made silicon alternatives. To me it makes some sense, then, that the human brain evolved a workaround by allowing for parallel computing at scale. That explains how we're able to carry out complex lingustic and visual processes without casting off the protective bubble of the telomere, exposing ourselves to all sorts of cancers and living excessively long lives in slow motion (a joke; predation would've wiped us out faster than cancer). So, regardless of whether you agree with it, I'm siding with the [connectionist](https://en.wikipedia.org/wiki/Connectionism) view throughout this post.

Okay. With those definitions out of the way, we're left with two distinct boundaries:

	1. Memory
    2. Read/Write Speed

## 1. Memory
In the context of lucid dreams, this means that exceeding some arbitrary memory limit "breaks" the dream. Here I consider a "break" to be a failure to continue the same unhindered rendering of an image at a sustained pace. But there's an immediate and glaring issue here: how does the brain process data? Is there a universal, mental language for ideas, for commands, for images? There may be some kind of language for thoughts according to the representative theory of mind, but in my short time researching this question I've yet to find a working estimate for the size of a mental word, image, or concept. I do assume that different mental operations also differ in cost; it's likely more taxing for the brain to produce a detailed map of a city than to think of a single word. Sadly I think this kills any illusion of satisfactorily resolving the size of our memorial dream budget, but at least we know that theoretically, dreams certainly can "break", and that trying to render too much, too fast can be a culprit.

Another concern is that memory probably varies per person. And when you consider that memory might be dynamically allocated... well that just complicates any sort of estimate even further.

## 2. Read/Write Speed
Fear not, though - you didn't _entirely_ waste your time reading this. I did manage to find an estimate for the brain's read/write speed (I also never promised to answer the question, I just said I was interested in reading into it). 

[This claim from 2009](https://www.technologyreview.com/s/415041/new-measure-of-human-brain-processing-speed/) seemed to indicate that based on an average of a particular reaction time study, the experimental upper bound was somewhere around 60 bits per second.

![temporal.png]({{site.baseurl}}/images/temporal.png)

Yes, I'm obviously wary of saying this is anywhere near a conclusive answer. For starters, it comes from a single paper. Additionally, its author agrees with what you might regard a common-sense objection: it seems irrational to believe that the brain assigns equal importance to all tasks. Change the experimental parameters and have subjects sleep, and you might suddenly see an entirely different speed based on the diminished or heightened importance of the mental state.
