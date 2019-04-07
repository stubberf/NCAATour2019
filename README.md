# NCAATour2019
Analysis of NCAA Men's Basketball Tournament using PageRank Algo.

The NCAA tournament is an exciting time, and everyone seems to be filling out brackets. [ESPN](http://www.espn.com/chalk/story/_/id/18901384/70-million-brackets-104-billion-bet-ncaa-tournament) estimated 70 million brackets were filled out in 2017. So, after watching a few of the close games so far, I decided I wanted to try and fill out a bracket too. I needed someway to rank the teams. Then it dawned on me what if I tried to use the PageRank algorithm.


PageRank was developed by the founders of Google to help them rank the quality of links on a webpage. Thus, helping them rank and sort the best webpage for the question you are searching for. Using PageRank, Google has come to dominate the area of search engine market share. Essentially, PageRank gives a higher ranking to those webpages who have many links from other highly ranked webpages. 

![Example of PageRank ratings for webpages. The bubbles represent webpages and the arrows represent links between them.](https://upload.wikimedia.org/wikipedia/en/thumb/8/8b/PageRanks-Example.jpg/400px-PageRanks-Example.jpg) Therefore, if your webpage on the history of basketball has a lot of links to it from highly ranked sites like Wikipedia, or ESPN then your site will be highly ranked also. I wanted to try this algorithm out for choosing NCAA teams.


So, instead of talking about the quality of links to a webpage I am interested in the quality of a win by a team. Teams who beat highly ranked teams become highly ranked also. For each team in the tournament I looked at their team record through the season, including conference championships. I used their wins and losses as links to webpages and ran the PageRank algorithm.


So, how did it turn out? The algorithm predicted Duke to win it all. This is no big surprise as they were the number 1 rated seed coming into the tournament. I started working on this when the teams were playing to make it into the Elite 8 but finished just before the Final 4 games started. Obviously, Duke did not make it to the Final 4. Of the 60 games that have been completed so far this version of the algorithm predicted 37 correctly. (To see the full predicted bracket, [click here](https://github.com/stubberf/NCAATour2019/blob/master/fillable-march-madness-V1.pdf)) Not perfect, but better than 50%. Additionally, if you use the common scoring this bracket would beat the [average bracket](https://www.ncaa.com/news/basketball-men/2019-02-27/march-madness-how-do-your-past-brackets-stack-competition) over the last 3 years. I consider that performance pretty good. Based on the current teams in the Final 4, Michigan-State and Virginia are predicted to move to the final round with Virginia slightly (by the smallest margins!) ranked higher than Michigan-State. Let’s see if these predictions are right.
