# String-Pattern-Matching-Linear-Time
Using Python, created an algorithm inspired by Rabin-Karp Algorithm for string pattern matching in linear time. 
It works in linear time as the singular for loop runs O(n-m+1) simplified to O(len(str)). 
Since I create a set of all possible substrings of length of possible pattern and According to Python wiki: Time complexity, a set is implemented as a hash table. So you can expect to lookup/insert/delete in O(1) average. 
