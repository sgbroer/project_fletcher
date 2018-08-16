# Project Fletcher

## MVP Proposal

### Domain
For Project 4 I plan to use NLP and clustering tools to examine online political discourse on Reddit. Specfically, I would like to create a bot that (attempts) to engage in and support civil political discussion. I have often been frustrated by the sometimes aggressive and tribe-like nature of the typical modern political discussion, especially online. Inspired by (excessive media coverage of) Russian influence in the 2016 election using troll bots online to promote and insight divisision among US voters, I would like to make an attempt at a similar task for the opposite ends.

### Data
I plan to use Reddit data both from the API and from data dumps available [here](http://files.pushshift.io/reddit/). I plan to focus primarily on the /r/NeutralPolitics community where I have personally found communication about politics to be well-reasoned and effective. If time allows for an extension, I would like to create similar bots from subreddits across the ideological spectrm and see how they comunicate with each other

### Known Unknowns
Although I have started to look at the Reddit data (the dumps in particular are already in quite a nice useable fomrat), for both my other projects I ended up spendinh more time prepping the data than I anticipated so I expect a similar thing to happen for this one. I plan on using some of the relatively simple approaches like topic modeling and we have employed in class already to get a MVP up and running. The plan as I currently have it imagined is to do vecotrize the full corpus, try some different dimensionality reductions (LSA, word2vec, LDA), come up with some topic clusters, then train NaiveBayes models on each cluster. The final bot would assign a document to a cluster (with the probability/makeup simplification) and respond accordingly. Since we have done exercises in each of these in class already, I don't see it being inordinately difficult. I have little idea how difficult it will be to actually implement the bot and set it free in the wild. Depending on the timing, If I get the basics down, I would like to go back and employ some more difficult techniques for generation (especially an NN), but that may be overly optimistic. 
