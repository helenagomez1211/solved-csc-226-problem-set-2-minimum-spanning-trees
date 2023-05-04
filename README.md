Download Link: https://assignmentchef.com/product/solved-csc-226-problem-set-2-minimum-spanning-trees
<br>
<h1>Minimum Spanning Trees</h1>

1            Programming Assignment

Theresa May, having just watched Shaun of the Dead, becomes worried that a zombie revolt is imminent. Should this happen, a natural fear is that the zombies will organize clandestine meetings, pool their collective minimal brain power, and ultimately push for “Zexit” (Zombie Exit), thereby crippling the eponymous unity of the UK.

Therefore, May creates the Ministry of Zombie Affairs, to be headed by Simon Pegg. Simon decides that the best way to prevent zombie meetings is by scrapping London’s current road network and replacing it with a network with the property that any two places are connected by precisely one path. This way, zombie drivers easily can be stopped using minimal blockades. Unfortunately, nearly all the funds required were spent on billboards warning of Zexit, and so Simon needs to construct a road network whose total length is minimal in order to minimize construction costs. More formally, the problem is described by the following Input and Output.

Input:               An edge-weighted graph <em>G </em>of <em>n </em>vertices. Each edge weight corresponds to the cost of constructing a road between two places in London.

Output:             The cost (sum of the edge weights) of the minimum-cost solution.

A Java template has been provided containing an empty function mst. This function takes a two-dimensional integer array <em>A </em>that represents the weighted graph in the form of an adjacency matrix. This function returns the sum of the weights of the edges in a minimum spanning tree of <em>G</em>. Your task is to write the body of the mst function, which can include calls to helper functions that you write. Your code is not required to check for incorrect inputs or incorrectly-formed input data.

You must use the provided Java template as the basis of your submission. You may not change the name, return type, or parameters of the mst function. The main function in the template contains code to help you test your implementation by entering test data or reading it from a file. A sample file is also provided (see the comments in MST.java for the file format). You may modify the main function or any other function, because your submission will be tested using a different main function. Only the contents of the mst function and associated helper functions (if any) will be marked.

2          Evaluation Criteria

The programming assignment will be marked out of 40, based on a combination of automated testing (using large graphs) and human inspection.

You are to implement Kruskal’s algorithm, equipped with the Weighted Quick-Union version of Union-Find (which you also are to implement). If implemented correctly, the running time of your code should be O(|<em>E</em>|log|<em>V </em>|). The marks for each submission will be based on both the asymptotic worst case running time and the ability of the algorithm to handle inputs of different sizes. The table below shows the expectations associated with different scores.

1

CSC 226: Problem Set 2

<table width="450">

 <tbody>

  <tr>

   <td width="56">Score</td>

   <td width="394">Description</td>

  </tr>

  <tr>

   <td width="56">0 – 15</td>

   <td width="394">Submission does not compile or does not conform to the provided template.</td>

  </tr>

  <tr>

   <td width="56">16 – 30</td>

   <td width="394">The implemented algorithm is not O(|<em>E</em>|log|<em>V </em>|) or is substantially inaccurate on the tested inputs.</td>

  </tr>

  <tr>

   <td width="56">31 – 40</td>

   <td width="394">The implemented algorithm is O(|<em>E</em>|log|<em>V </em>|) and gives the correct answer on all tested inputs.</td>

  </tr>

 </tbody>

</table>

To be properly tested, every submission must compile correctly as submitted and must be based on the provided template. If your submission does not compile for any reason (including even trivial mistakes like typos) or was not based on the template, it will receive at most 15 out of 40. The best way to ensure your submission is correct is to download it from conneX after submitting and test it.

You are not permitted to revise your submission after the due date, and late submissions will not be accepted, so you should ensure that you have submitted the correct version of your code before the due date. conneX will allow you to change your submission before the due date if you notice a mistake. After submitting your assignment, conneX will automatically send you a confirmation email. If you do not receive such an email, your submission was not received. If you have problems with the submission process, send an email to the instructor before the due date.

2