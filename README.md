# SubsetSum-NP
Greedy Approach to a NP problem, Subset Sum.
The Pdf file consists a detalied analysis.
CONCLUSION 
 
To summarize; we have observed that subset sum problem is an NP-complete problem. We have demonstrated that Subset-Sum problem is a reduction from 3-CNF SAT and the problem itself is NP-hard. It needs to be indicated that there is not an exact algorithm that solves the problem in polynomial time after some extent. There exist approximate approaches just like we have used. Greedy approach is one of them that we have worked on. We have analyzed and examined this algorithm in our report and demonstrated that the greedy approach does not always come up with the solution.  
 
Despite the algorithm that we ran while experimenting occasionally fails, we have obtained an approximate of between %60-%75 success rate while running the greedy algorithm on different iteration levels and set sizes. On average, accuracy rates increased with proportion to wider set-sizes. Based on that inference; we generated different sets with different increased set sizes to display the increasing accuracy rates. In that stage of the experimentation; we also inferred increased set sizes also result in increased running mean times. An improvement in the algorithm would be to find an even more efficient k-value (capacity) to both improve the running times and accuracy ratings. The value for maximum possible range for an element in the set (element size) is another possible parameter that could be improved. However; based on our findings; in general, multiplication of set size and the element range must at least be equal to K to obtain a higher accuracy.  
 
Lastly, when analyzing for time complexity; we obtained that for all running time graphs; the graph behavior is quadratic. Even though the graph behavior seems like it’s concave instead of convex at subset size of 150; this is due to the increased possibility for the algorithm to return a correct output in longer subset sizes. This probability increase results in a relatively faster performance at subset size of 150 compared to previous sizes such as 50 and 75.The algorithm running time was expected to be more at 150, however, since the accuracy is very high at that level, the algorithm ran faster than expected which is understandable. In the end, the inference 

 
20 
 
about the algorithm’s performance still stands true, previous subset sizes show strong implications of quadratic behavior. 
 
 
 
