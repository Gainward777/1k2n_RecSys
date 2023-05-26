# 1k2n
The selection of recommendations in shareware applications is a rather specific process, since it is necessary to recommend not the most relevant content, but the closest to it. In order to continue to hold the user's interest by maximizing the display of ads, it is necessary to "be on the edge" of interests, but not "cross" it.</br>
This is a recommendation system based on a set of likes and dislikes of users, based on the idea that when we talk about visual content, we cannot say exactly what the user liked. It may well turn out that this is precisely the style of the work, without regard to content, or only content, or maybe these are some specific features. At the same time, in a sufficiently large sample, different categories may contain content with similar features. Accordingly, it is possible to select both a large amount of content similar to what similar users liked, and a certain amount of content close to what the target user liked, and at the same time is not in his favorite categories, nor in the favorite categories of similar users.</br>
An ensemble of nearest neighbors was chosen for implementation due to its simplicity and good interpretability. At the same time, [criticism](https://arxiv.org/pdf/1907.06902.pdf) of relatively similar, poorly interpreted algorithms was taken into account. 
