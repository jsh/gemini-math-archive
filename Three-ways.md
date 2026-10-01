What you have uncovered is a striking instance of equidistribution governed by **Foata’s Fundamental Bijection** and the theory of **Stirling statistics** on the symmetric group.

### **The Overarching Framework: Species and Bijections**

In the language of combinatorics, what unites these decompositions is that they are all canonical representations of permutations counted by the signless Stirling numbers of the first kind, denoted as \$\\left\[ \\begin{matrix} n \\\\ k \\end{matrix} \\right\]\$.  
The overarching machinery that describes all such sub-classes is **Combinatorial Species theory** combined with **foatisation**—transformations that map one permutation statistic onto another while preserving the joint distribution of cycle counts and component lengths. Whenever a recursive or greedy parsing rule on a sequence mirrors the canonical cycle notation (such as standardizing maximum/minimum elements or building standard parsing trees like Cartesian trees), it inherits the cycle index polynomial of the symmetric group:

\$\$\\sum\_{n=0}^{\\infty} x^n z^n \= \\prod\_{j=1}^{n} \\left( 1 \- z t^j \\right)^{-1}\$\$

### **Other Members of the Stirling Clan**

Beyond your three examples, several other classic sequence decompositions share this exact statistical profile:

* **Left-to-Right Minima (or Maxima):** Decomposing a permutation by splitting it whenever a new running minimum is encountered.  
* **Permutation Descents and Rises:** Certain canonical factorizations of permutations into monotonic runs (though some relate to Eulerian numbers, others map directly to Stirling structures under Foata's correspondence).  
* **Cartesian Tree Valleys/Nodes:** Decomposing a sequence via its Cartesian tree representation, where tree node properties reflect cycle structures.  
* **Lehmer Code / Inversion Table Partitions:** Grouping entries based on specific null-count configurations in inversion vectors.

Would you like to unpack how your "trend" and "streak" definitions map directly onto canonical cycle structures via Foata's bijection?