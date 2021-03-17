---
layout: single
title:  "What is an enterprise knowledge graph anyway?<br/>(Part I)"
header:
  overlay_image: assets/images/IMG_0076.jpg
  overlay_filter: 0.5 # Same as adding an opacity of 0.5 to a black background
  #overlay_filter: rgba(20, 55, 60, 0.5)
date:   2021-03-17 22:00:00 +0100
---


In this post, I'll approach the question top down.
I.e. not looking at what an enterprise knowledge graph is made of,
but at its function for an organization.

# First things first: What is enterprise data management?

Let's start with a question that seems to be easier to answer: What is enterprise data management?
Is this easy to answer?<br/>
Data - the conventional marketing story for what happens with data goes like this:
We collect and create raw data, process it and put it in context to get information and finally do some analytics to gain knowledge (the DIKW pyramid, with W for wisdom).
And we talk about enterprise data, because there is so much, it is hard to reconcile and needs protection.<br/>
Honestly, from my perspective this story, no matter how often told, leads people completely astray. It proposes dependencies that are frankly a distortion of the full picture and distracts from the processes taking place.

So let's start over and begin the journey anew with the other part of the term enterprise data management:
the enterprise - as a large organization with a mission.

# Organizations

Stating the obvious will help us to untangle the picture:
Everything an organization does is ideally contributing to support the strategy set by the board. But the board doesn't know all the details of what needs to be done and even less how. The way it works is outlining the targets and delegation of those to sub-organizations that have a more detailed understanding, the know-how. They will break down their targets to an actionable program and delegate again further down.<br/>
The challenge on all levels is to strike a sensible balance between central control and local autonomy (for faster adaption). The upper control loop (e.g. of the board) has to care for more longterm direction and reacts slower to events than sub-organizations closer to actual operations.

This may sound strictly hierarchical, but that is not the relevant point. Instead the point is that handing over from one process to another and getting feedback on the outcome always means being insulated from the details of the other process and a delay until results come back.<br/>
As every person and organization has a limited capacity for detail this is exactly how it has to be. There is an agreed understanding of input parameters of other processes and outcomes to be expected, but there is at best a rough understanding of the inner workings and all the related details.
So the reality is: there are multiple interconnected systems and subsystems (entangled in a multi-scale process).<br/>
Each having their own point of view and their own agency (own capacity for decisions and actions) driven by their specific incentives and constrained by task assignments and internal controls.

# Data

Data is the means to coordinate the different actors within this network of agents, it is the interfacing object between processes.<br/>
But data is never _raw_. It is always the result of a process that operates with its own model and a set of classifications that implicitly (e.g. what is left out) and explicitly shapes the data it creates.
Taking a broad perspective on what data can be - namely any recorded information that can be passed around, stored and copied - makes clear that this has always been the case. This was true even before there was any IT in organizations - usually just as paper-based process instead of a digital one.

# Automation

A new challenge when using data comes with automation. When you cut out the human receiver, data has to be 100% formalized.
This is the only thing we think of today, when talking about data (the rest is now _content_ or _"unstructured" documents_).
It comes in formats (syntactical conventions) and there is (hopefully) an agreed interpretation how the different parts are supposed to be interpreted - what they refer to.

The price to pay for automation at this point is a ton of shared conventions that need to be organized and maintained.<br/>
This is the essence of enterprise data management:
Making sure, that all data used across the whole organization is documented, aligned and follows some shared guidance. Depending on how this is done, there is often a lack of flexibility and adaptability as part of the price tag.
In the best case data and automation almost invisible support the tasks that need to be done. In the worst case they become obstacles, that require extra care and massively increase the overall complexity of what needs to be handled to get things done.

# Models

To achieve the best case (almost invisible automation), organizations need abstractions that perfectly fit to their model of themselves as an organization and its operations. Needless to say that whenever the situation changes, immediate adaption is crucial.<br/>
This follows from the good regulator theorem which states that _every good regulator of a system must be a model of that system_.
Those models are what we consider knowledge.
Knowledge is relative to the agent (in its mind for a person, in its document repository or data and knowledge bases for an organization).<br/>
Now here is a critical problem, when we take our previous description serious:
When describing the organization we stated that control is distributed and every agent has their own point of view of its environment and subsystems which is typically a coarser model than the models which are actually used to regulate these other parts. BI minded people may think _Ah! Data aggregation._, but that is only part of the answer. The amount of details lost by translating from one model to the other can be more substantial and subtile.

Attempts that ignored this aspect and tried to build an aligned detailed model to be used uniformly across the whole organization, were always a total failure.
So this is the challenge: Many models in different granularity, that are STILL aligned.

# Enterprise Knowledge Graphs

This is where knowledge graph technology and formalisms kick in. They provide the required capabilities and characteristics to do exactly that:
Align many models in different granularity that can overlap and link those to actual data. A knowledge graph is not only providing machine readable data, like all other databases, but also machine and human readable models AS data. <br/>
An enterprise knowledge graph is a virtually connected mesh of (sub) knowledge graphs.
It covers all critical data concepts, provides globally unique identifiers, ownership and models and is typically combined with a uniform lookup mechanism.

The promise of enterprise knowledge graphs is slashing the complexity of data and automation by at least an order of magnitude. This is achieved by avoiding model mismatches, providing alignment between different lenses and by avoiding data copies that start a life on their own.

To be continued in Part II...
