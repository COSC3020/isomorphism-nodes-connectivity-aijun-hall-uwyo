# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

<hr>

$A$ and $B$ are two graphs that have the same number of nodes, and are completely connected- as defined in the prompt.

If they have the same number of nodes AND are completely connected, this must mean that graph A and graph B both have the same amount of verticies, and the same amount of edges.

$\text{number of verticies in graph A} = \text{number of verticies in graph B}$

$\text{number of edges in graph A} = \text{number of edges in graph B}$

Because of these two properties we can state that there is a bijection of:

$f: V_1 \ \rightarrow \ V_2$

Meaning that there are no duplicate verticies, and no leftover verticies. Since the graphs are both described as completely connected, we can also state the same for edges.

So for every vertex in A, there exists an equivalent distinct vertex in B, and for every edge in A there exists an equivalent distinct edge in B. Both statements also hold true in reverse, for every vertex and edge in B, there exists the same in A.

The above bijection and property description fullfills the formal definition of isomorphism given above, and therefore graph A and B are isomorphic.

- Referenced https://www.geeksforgeeks.org/graph-isomorphisms-connectivity/

- Referenced https://en.wikipedia.org/wiki/Graph_isomorphism

"I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice."

