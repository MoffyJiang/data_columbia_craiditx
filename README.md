# data_columbia_craiditx

## Copyright (c) 2019 CraiditX Ltd. All rights reserved.

## some words

#### 2019-10-11

- There are two ways for us to deal with graph data, running algorithm directly on the relation data (the edge sets generated in notebook_2) or using Neo4J (a better option for offline researchers). NetworkX is used in the sample code but I highly recommend NOT to use it.

- Data generator in notebook_1 is to avoid too much memory usage. But clearly in the sample code I still load the whole data into memory. I'll revise it slightly so that the generator can read directly from text file iteratively instead of loading them.
