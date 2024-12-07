# Isomorphism

Prove that if two graphs $A$ and $B$ are isomorphic they do *not* have to
be completely connected. I have started with the formal definition of
isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

If two graphs have the same number of nodes then each node in graph A corresponds to a node in graph B, |V1| = |V2| = n, both sets had the same number of n (nodes). They don't have to be completely connected they just have to have the same number of edges and degree sequence for each node that corresponds with the node in the other graph. For example if x and y in graph a are not connected then the node they map to in graph b should not be connected either, on the other hand if they are connected in one graph they have to be connected in the other. 

Graph A: nodes- (a,b,c,d) edges- ({a,c}, {b,d}, {a,d}) 
Graph B: nodes- (w,x,y,z) edged- ({w,y}, {x,z}, {w,z}) these graphs are isomorphic but not completely connected.

“I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.”
