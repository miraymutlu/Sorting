<h1 align="center">Insertion Sort</h1>

<h3> 1) Insertion sort of [22,27,16,2,18,6] </h3>

    [22|,27,16,2,18,6] 
    [22,27|,16,2,18,6]
    [16,22,27|,2,18,6] 
    [2,16,22,27|,18,6] 
    [2,16,18,22,27|,6] 
    [2,6,16,18,22,27|]
    Result => [2,6,16,18,22,27]
    
<h3> Step by step, </h3>    

    [22,27,16,2,18,6]
    [22,27,16,2,18,6]
    [22,16,27,2,18,6]
    [16,22,27,2,18,6]  
    [16,22,2,27,18,6]  
    [16,2,22,27,18,6] 
    [2,16,22,27,18,6] 
    [2,16,22,18,27,6] 
    [2,16,18,22,27,6] 
    [2,16,18,22,6,27] 
    [2,16,18,6,22,27] 
    [2,16,6,18,22,27]
    [2,6,16,18,22,27]
    Result => [2, 6, 16, 18, 22, 27]
    
    
<h3> 2) Big-O </h3>

    Worst Case : O(n^2)
    Avarage Case : O(n^2)
    Best Case : O(n)
    
<h3> 3)Time Complexity </h3>

<h4>For example, we are looking for 2 in this array. </h4>

    Worst Case : [27,22,18,16,6,2]
    Avarage Case : [6,2,16,18,22,27]
    Best Case : [2,6,16,18,22,27]
    
<h3> 4)Which case would 18 suit after the array is sorted? </h3>

    Average case because 18 is in the middle of the array.
    
 
