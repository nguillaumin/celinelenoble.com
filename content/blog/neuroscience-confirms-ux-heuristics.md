+++
date = "2018-01-28T16:01:25-08:00"
title = "How neuroscience confirms UX heuristics"
description = "The Bayesian interpretation of the brain sheds a new light on well-known design principles."
+++

 <div class="overview">

 Overview | <i class="fa fa-bookmark"></i>
 ---------|---
 10' read | The Bayesian model of brain decision mechanism supports UX heuristics and can help us become better UX designers.

 </div>

Interaction and UX designers have long known and used heuristics to guide the creation of user-friendly interface. We know empirically that these principles work, and they make “common sense”. These heuristics themselves aim to make interface “intuitive”, but common sense and intuitive are concepts hard to define precisely.

Research in neuroscience have proposed a new interpretation for how the brain works and how decisions are made, namely the Bayesian brain. When comparing the known heuristics and this new interpretation model, we find numerous similarities. Understanding the Bayesian brain should help designers go beyond vague concepts of “common sense” and “intuitive” to understand why their heuristics work or not.


## Our brain is a statistician
The Bayesian brain is a way to describe how our perception works. We receive millions of stimuli each second from all our sensory nerves. Most of these signals, as numerous as they are, are still ambiguous. When we receive a certain amount / shape of light in our retina, multiple objects outside could produce this same pattern. However, most of the time, we don’t consider all the possible objects, we identify instantaneously the right object. 

The Bayesian brain theory explains how, behind the scenes, the brain operates: it uses probability and equations similar to Bayes theorem to give us only one a single answer. Even though we are aware of a single object, our brain has processed all the possibilities and determined the most likely one, using Bayes theorem, and presents this most likely possibility as the only one. Several experiences show the power of prediction of this theory, and how the physical neuron network can actually perform these kinds of calculation.

The Bayesian brain theory makes a distinction between the unconscious, statistical treatment of stimuli, which includes many alternatives with their own probability and our awareness of a situation, which is (should be) unique. Bayes theorem uses two factors to calculate the posterior probability / make an inference: the known probability of a given situation, and previous knowledge. Decision in this model is based on the resulting inference and a function of gain / loss.



## Why is the fact that our brains use probability so important for UX designers? 
First, this emphasizes the fundamental ambiguity of all types of signals, including the interfaces we design. Optical illusions work by leveraging this signal ambiguity and the processing done by the brain to present to us the most likely solution(s) based on our previous experience. They show us how our perception is a brain construct rather than a exact reflection of reality. Optical illusions are only extreme cases of how we constantly transform our sensations into perceptions. Thus, designers need to reconcile themselves with the inherent ambiguity of all constructs (while trying to minimize it) and cease to blame “dumb” users for their misunderstanding.

{{< figure src="/images/optical-illusions.jpg" title="Which green circle is the biggest one?" >}}

Second, Bayes theorem gives us clues on how to minimize this fundamental ambiguity, and make the right interpretation stand out among all the possible ones. Luckily, these clues map exactly to the already known heuristics, but now we have an idea why they work so well. 

Third, we can now define more clearly what has long being elusive: the concept of “intuitive” itself and understand that there might not be any kind of universal intuitive system, but that what we consider as “intuitive” is mostly previously learned rules, so well internalized that we consider them as “natural”. 


## Minimizing ambiguity
The Bayesian theorem produces accurate inferences based on two factors: the known probability of a given situation and the prior probability of the alternative that is considered (based on our previous experience).

As a designer, we need to use each of these aspects, so they are all aligned in the same direction: 
-	The given situation is the stimuli: the visual / audio / text signals must all convey the same message: green checkmark with a high pitch sound: positive / red cross with a loud low pitch sound = negative. 

{{< youtube JVwLv_r5dI0 >}}

	
Of course, not all situations are so simple, but even things that simple can be messed up. Some card payment terminals emit a low pitch sound while displaying a “payment accepted” message, resulting in confusion in the client, and the need for the cashier to reassure them that all went well. This might seem minor, but I bet the few seconds wasted everywhere this type of terminal is used add up to significant productivity loss. 

- Prior probability represents what we call in design mental models. They are the results of the successful inferences made by the user in the past, often associated with a causality system. We learned to associate green with something valid or positive and red with errors or wrong way signal. 

These should be a well-known quantity for designers: through competitive research, we know other existing systems and interfaces; through user research, we know which tools our users manipulate, what their mental models are, etc. The design should leverage this known quantity to make the new interface or system familiar, reinforcing previously learned patterns. 


Then, the user must make a decision. According to the decision-making theory using Bayesian interpretation, we make our decision based on the inference made using Bayes theorem and a gain / loss function. 

{{< figure src="/images/decision-process.png" title="Perception-Action loop according to Bayesian perspective" attr="Source: Ernst & Bulthoff, 2004; quoted in S. Dehaene, 2012" >}}

This maps perfectly onto other UX heuristics: clearly state the outcome of an action and keep the user informed on the system status. Having clear information on the system status and outcome will help the user make better, quicker decisions. 



## What does intuitive mean? 
When we act seamlessly, without even thinking, is when we say that things are “intuitive”. Based on what we said previously, we have a better grasp of what make things / interfaces feel intuitive or not. 
We make quick, almost imperceptible decisions when all the mentioned factors align perfectly: signals, mental model, know status and outcome, because our Bayesian brain has calculated a very high probability for the right alternative, and very low probability for all other possibilities.

Something is not intuitive when the multiple alternatives processed by our brain cease to operate at an unconscious level and make their way into our awareness. When does that happen? When several alternatives have similar probabilities. Then our well-trained Bayesian brain lets us become aware of several possibilities, the most likely ones, creating confusion.

Thus, for things to be intuitive, there needs to be one clear winner among all the alternatives. However, as the probability is not only a function of the stimuli, but also of previous knowledge, there is no way to create an interface that would be universally intuitive. We shouldn’t say that things or interfaces ‘are’ intuitive by themselves. We can only say that they ‘feel’ intuitive for this category of users. Each person has her own previous experience, that might influence differently her perception of a given interface. 

As an example, there is no answer to the question whether Apple or Microsoft is more intuitive: users of each system have learned patterns of usage, which became “intuitive” to them. Making the switch to a system with different patterns becomes very costly. If you eliminate the notion of a naturally intuitive system, and replace it with learned patterns, then there is no intrinsic superiority of a system compared to another. 

As a designer, this means that you need to know the audience you’re designing for intimately enough that you know their mental models. This is typically achieved in one of two ways: 
-	Designers who are so immersed in a given “culture” that they share most patterns with their users. These designer will use the same patterns in their design, without even thinking about it. They might be great designers in a specific context, but they won’t perform so well in another, because they not only ignore the patterns of this new context, they don’t have an explicit understanding / conceptualization of what make things “intuitive” for some people and them and not others (these are the designers who say that users are dumb).
-	Designers who research and identify the mental models of their expected users. Of course, they also have their own learned patterns, and are not completely immune to the illusion of things being intuitive, but they reflect on their own learned habits, acknowledge their preferred patterns, so they can more easily distance themselves and learn other ways of doing things. They don’t trust their "intuition" so much and prefer hard evidence.



For more on the Bayesian brain, see
[a series of lecture by Stanilas Dehaene, College de France, 2012 (in French)](http://www.college-de-france.fr/site/stanislas-dehaene/course-2011-2012.htm)


Amy Perfors, Joshua B. Tenenbaum, Thomas L. Griffiths, Fei Xu,[A tutorial introduction to Bayesian models of cognitive development](http://ml.cs.washington.edu/www/media/papers/tmpf2n50d.pdf), Cognition, Volume 120, Issue 3, September 2011, Pages 302-321.

Marc O.Ernst, Heinrich H.Bülthoff, [Merging the senses into a robust percept](https://www.sciencedirect.com/science/article/pii/S1364661304000385), Trends in Cognitive Science, Volume 8, Issue 4, April 2004, Pages 162-169.





