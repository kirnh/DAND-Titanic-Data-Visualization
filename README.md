###README.md

This file contains descriptions and discussions related to decisions made during the creation of the Titanic Data Visualization.

###Summary

The sinking of the RMS Titanic occurred on the night of 14 April through to the morning of 15 April 1912 in the North Atlantic Ocean, four days into the ship's maiden voyage from Southampton to New York City. The ship hosted 2,224 passengers and crew out of which more than 1500 died when she struck an iceberg at around 23:40 (ship's time) on Sunday, 14 April 1912. 

The Titanic Data Visualization tries to explain a few factors that seemed to have affected the survival rate of the ship's passengers by analyzing a dataset containing information about 891 out of the total 2,224 passengers.

###Design

1. Since the main aim of the visualization was to show how various features affected the survival rate, the y axis or the dependant variable had to be survival rate. While the independant variable or the x axis was the feature that seemed to have affected the survival rate. I selected gender, class of travel and age group as the three features that affected the survival rate of passengers since the exploratory analyses of the dataset led me there. These three independent features along with the dependant survival rate became the base for my three explanatory graphs. Bar type graph was the best option since my independent variables were all categorical in nature. Also since the y axis was survival rate, i could use stacked bars to show both survived and died percentage together which would add more information without any redundancy! The last thing I did was arrange my categories along the x axis such that the blue bars representing the % survived became shorter as we moved to the right. This would give a nice flow to the reader in understanding the graph. The size of the text in the graph were properly adjusted as well. All of the above formed a part of my first iteration of the visualization (index1.html file in the Gist).   

2. The Feedback #2 given below is taken as a reference for further tuning of the visualization. This includes adjusting the animation part of the dimple code such that it does'nt dilute the attention of the reader while looking at the graphs. However, the gridlines are retained since it isn't much of a distraction and might be useful for readers who miss out on the tooltip dialogue box showing the percentage. The visualization thus obtained is satisfactory and is considered as the final iteration (index.html in the Gist).

###Feedback and Iteration

-Feedback #1: This is a feedback on the first iteration of my visualization given by a friend.

1. I see three graphs representing Survival rates by-- Class of Travel, Gender and Age group.
2. People travelling in Class1 had better chances of survival. Females, however, are more likely to survive. Almost every child has survived (about 90% of them).

-Feedback #2: This is a feedback on the first iteration of my visualization through the Udacity's forums.

The visualization looks good. This is a relative straightforward dataset, also the idea that's communicated is not hard to understand either. That being said, there isn't much to comment on, maybe I can just nitpick a bit and offer some different perspectives:

1. Since the proportion comparisons are quite clear, and also you have tooltip to show the actual percentages, maybe you can remove the background gridlines which don't seem to offer much in extra.
2. The animation looks really cool when clicking on a button, but again, the value it adds doesn't seem to be justified considering the possible dilution of the reader's attention; also it seems that there's some traces left after the animation.

###Resources

1. Udacity DAND P6 forums. 
2. Sinking of the RMS Titanic - Wikipedia
3. My project on EDA of the Titanic dataset.
