# Netflix-Recommender-System

This is a Netflix recommender system implementation using Hadoop MapReduce.
We utilized item-based collaborative filtering algorithm to make recommendations, which is one of the forms of collaborative filtering 
for recommender system based on the similarity between items calculated using user's ratings of those items.

The jar file containing the source code:

hadoop jar recommender.jar Driver /input /dataDividedByUser /coOccurrenceMatrix /Normalize /Multiplication /Sum

hdfs dfs -cat /Sum/*

#args0: original dataset

#args1: output directory for DividerByUser job

#args2: output directory for coOccurrenceMatrixBuilder job

#args3: output directory for Normalize job

#args4: output directory for Multiplication job

#args5: output directory for Sum job
