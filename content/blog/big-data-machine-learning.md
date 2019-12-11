+++
date = "2016-09-08T14:28:35-07:00"
description = "Machine learning is a powerful, but be careful how you use it."
title = "Machine Learning: Opportunities Are Not What You Think They Are"
+++


> Disclaimer:
> I'm not an artificial intelligence or machine learning specialist, but I've taken an interest for this topic for quite a long time. With this caveat, I still believe that ordinary citizens should take part in a debate that is crucial for society, considering the quick pace of adoption of machine learning techniques and the potential consequences.



I'd like to reflect on machine learning from the perspective of social sciences. I think the debate on possible bias in machine learning and big data algorithms is starting from wrong premises. It seems that those premises are based on a misunderstanding of how machine learning works, and consequently, what we want them to accomplish. 

The first misunderstanding is to think that because it's a machine, it's going to be free of bias, and therefore can't discriminate. Indeed, as an object made of processors, and for now still deprived of self-awareness, a learning machine is "objective", as in the opposite of "subjective", but that doesn't mean it is free of bias. The biases are not in the machine itself, but in the data that is used to train the machine. Data themselves are often portrayed as "objective", but they are only a limited representation of reality, not reality itself. (We could go on and question the nature of reality itself, and its existence independently of any subject, but this would take us too far in the philosophical direction). [See this article for how bias invits itself in data analysis.](https://medium.com/@akelleh/understanding-bias-a-pre-requisite-for-trustworthy-results-ee590b75b1be)

{{< figure src="/images/matrix.jpg" title="Are we living in a vast simulation?" attr="Source: www.zastavki.com/eng/Movies/wallpaper-1339.htm" >}}

The second misunderstanding is a natural consequence of the first: as machine learning is thought to be "objective", learning algorithms would do a better job than humans at a ton of things. We have a tendency to positivism, the belief that technology and science can solve all our problems, almost miraculously. Some claims about machine learning sound indeed over-enthusiastic. So machine learning or big data algorithms are used in many situations, even though this might result in small or large failures. Machine learning specialists themselves still struggle with what they call the interpretability of machine learning, basically why the machine produces the results they produce. For more details on this topic, read [this article.](http://nautil.us/issue/40/learning/is-artificial-intelligence-permanently-inscrutable?)

What machine learning does, and does very well, is to take in a huge amount of data, and make a synthesis of all this data for human consumption. No human can tackle the large amount data on the order we're talking about. The synthesis that is produced is a kind of clearer picture of what is going on in the initial data. It allows humans to get a better understanding. Machine learning could be the reverse equivalent of a microscope for social science. The microscope enlarges the very small so it's visible to biologists and physicists. The "macroscope" of machine learning reduces extremely large and complexe data into something understandable by sociologists and anthropologists. 

{{< figure src="/images/twitter-bot.png" title="When a bot learns from tweets" attr="Screenshot" >}}

I think that having this powerful tool to better understand how society works can be an incredible opportunity for social sciences. I don't see what happened to the [twitter bot](http://www.cnet.com/news/twitter-turned-microsoft-ai-teen-tay-into-horny-foul-mouthed-sex-bot-racist/) as an accident or a flaw in its programmation. It was doing very well what it was programmed for, and it just surfaced things we usually turn a blind eye to. From a sociological and anthropological point of view, I think such experiments could teach us a lot. For that, we would need to use machine learning not to "predict the future", but to explore the present.

The trouble comes when this tool is not just used as an investigation tool, but as an operational one. When decisions are taken based on the picture produced by the machine. First, machines are tuned so they are able to reproduce reality accurately. This means that any use of machine learning is biased toward the existing state of affairs. 

There's a kind of tautology going on. Imagine machine learning is used more and more widely: machines are trained on data from the recent past, and they produce decisions that shape the immediate future based on this data. Then, possibly, new data is produced, which is then feed into the same or other machines... How would we escape the loop while still using machine learning? Distorting the data or tuning the machine so the outcome is "better" than the present? But what does "better" mean and who gets to decide? If you are satisfied with how society works now, machine learning seems the perfect way to perpetuate the present or immediate past indefinitely. If you're not satisfied, well...

Another problem related to the use of machine learning as decision tools that concerns me has to do with applied statistics. I can't figure out if it's a real problem, or just come from my limited understanding. I'll explain it here, and better informed people can tell me if I'm right. I've learned that statistics are true when applied to a large population, but that you can't use statistics accurately on a small sample. 

{{< figure src="/images/schrodingers-cat-meme.jpg" title="" attr="http://weknowmemes.com/2014/07/schrodingers-cat-walks-into-a-bar/" >}}

It seems to me that machine learning works a lot like statistics, even though the inner algorithms are different. Machine learning can be very good at making an overall accurate picture, but we don't task them to provide us with a global picture. Instead, we ask these virtual neural networks to give a prediction or make a decision on an individual basis. Take a prisoner soon to be released: what are his chances of committing a crime again? Big data algorithm might say: out of 100 prisoners, 67 will reoffend - 33 will stay clear. This is not the same as saying for one given person, that she or he has 67% chance of recidivism. The way I see it, this person's state is a bit similar to a quantum particle, with the superposition of two states (criminal, law-abiding citizen), like the cat of Schrödinger. Not only we don't know which state is prevailing nor which will prevail in the future, but we can't possibly know. Worse still, the decision that is made is certain to influence the outcome - like the observation of such a particle. 

If machine learning claims to be able to accurately and precisely predict an outcome regarding the behavior of a given person, not in a statistical way as stated above, then this raises the issue of free will (another philosophical debate). It would mean that past factors not only have an influence on your future, but they define it in such a specific way that an algorithm can predict it... Obviously, such a possibility is frightening, not only for the prisoners as in the example, but for all of us. More and more data are gathered about us, and more and more decisions are made for us without us even knowing about them (which ads, jobs offer or news you're likely to see for a start). Imagine a dystopian future where the life of each individual is defined by an Artificial Intelligence (check [Psycho Pass manga](https://en.wikipedia.org/wiki/Psycho-Pass) for an idea of what it might look like).

{{< figure src="/images/psycho-pass.png" title="Psycho Pass: when your life depends on the emotional score constantly calculated by an AI" attr="Screenshot" >}}

Machine learning is a very powerful tool to investigate human society. I believe it's not a panacea to solve problem and make decisions instead of humans, at least as long as we don't really understand why the outputs are what they are. Even so, it raises political, cultural and philosophical issues on a large scale. We need anthropologists and philosophers to work alongside computer scientists to examine the underlying assumptions made, and the impact of the large scale use of machine learning on society.


Two great articles on machine learning:

- Aaron M. Bornstein, [Is Artificial Intelligence Permanently Inscrutable?](http://nautil.us/issue/40/learning/is-artificial-intelligence-permanently-inscrutable?)
- Moritz Hardt, [Approaching fairness in machine learning](http://blog.mrtz.org/2016/09/06/approaching-fairness.html) 




