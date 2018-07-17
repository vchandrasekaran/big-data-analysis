# Big Data Analysis to find the optimal performance characteristics. 

## Skills: Big Data, Hadoop, MapReduce, Java, Tableau
In this project we will analyse the optimal performance characteristics relating to compression, intermediate compression, combiners, block size and the number of reducers. The aim of the project is to test these characteristics and find the optimal solution to improve the performance of the MapReduce tasks. 

The dataset used for this project is the weather dataset from ncdc. The MapReduce tasks were run on the different datasets which were with the above characteristics and the performance times were analysed.
###Test 1
First we analyse the number of reducers and the role of the reducers with regards to the performance. For this test we do not use a combiner or intermediate compression. The first test has one reducer and we perform the same test with 2,4 and 8 reducers one after the other. The graph given below shows the performance of the subsequent MapReduce tasks. 
![test1](https://github.com/vchandrasekaran/big-data-analysis/blob/master/Images/test1.png)





