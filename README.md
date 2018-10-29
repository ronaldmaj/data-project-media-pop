# data-project-media-pop
This repository contains a data analysis project looking at characteristics of popular media.
In essence, what are the differentiating features between something that is popular and/or
viral and something that is not.


The first area I investigated was audio, specifically the features of popular podcasts and 
comparing them to not so popular ones. Podcast listeners have been identified as a highly 
loyal audience and (importantly) one that pays attention to the ads played to them:
https://www.wired.com/story/apple-podcast-analytics-first-month/
A number of different analysis will be undertaken for episodes of popular podcasts:

-Fourier Transform to find the frequency spectrum of each file: is there a link between the
overall frequency spread and the popularity? Are higher pitches bad for repeat downloads?
Does the degree of spectral flatness and roll-off play a part?

-Find the length of gaps between speech segments: what is the optimal length? 

-Does speed of conversation play a role? 

-Through Google's AudioSet identify different sounds throughout popular podcasts. Are
there any categories that they use compared to their less popular counterparts? Use 
TensorFlow to create neural network (or other machine learning algorithm) to train 
a classification model for podcasts in order to identify the segments of the files.
https://research.google.com/audioset/index.html


Another area is video. YouTube is a massive repository of videos and millions of people
frequent the site everyday. It has become important not only for entertainment and news
but also education and training purposes as well. What features of videos lead to their 
success?

-Does the number of people in the video matter? Are vlog talking heads the most popular? 

-Does the number of jump cuts or scene changes affect the popularity?

-Is the length of the video important?

-Is there a color palette that detracts from a video?

These are all questions that I would like to look into.
