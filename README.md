# second-largest-number-in-an-array
# DSA question 3  
In this we have to find the 2nd largest element in the array  
so firstly we will define 1st element of the array as largest (largest = arr[0])  
Then define the 2nd largest element as any minimum number (slargest = -1 )  
Then iterate through the array and compare it.  
if(arr[i] > largest)  
and  
else if(arr[i] > slargest && arr[i] != largest).  
The Time Complexity will be O(N).
