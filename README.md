# Popular-Hashtags
In this project, it is required to implement a system to find the n most popular hashtags appeared on social media such as Facebook or Twitter. The hashtags along with their counts are given in an input file. It is required to use Max Fibonacci Heap to keep track of frequencies of hashtags and a Hash Table in which the key is the hashtag and value is the pointer to the corresponding node in Max Fibonacci Heap. Increase key operation needs to performed several times on the hashtags. Due to this reason, Max Fibonacci Heap is used as it has better theoretical bounds for increase key operation.