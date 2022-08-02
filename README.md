# RouteRec
Route Recommendation Algorithm Based on Preferences of Individual User Using Monte Carlo Tree Search
Route recommendation is a common application we are using every single day, especially when going for outdoor activities, going to office. There were already large amount of implementations and discussion for this algorithm in the industry. There are two major parts in the proposed algorithm:
1)	Using Supported Vector Machines to build the classifier model based on user preference routes and random generated unpreferred route samples
2)	Applying Monte Carlo Tree Search simulation to simulate possible routes between origin and destination, together with SVM model reward, to suggest the route recommendation for user
3)	Implementing the code of algorithm, including testing, and provide several ideas for future improvement
