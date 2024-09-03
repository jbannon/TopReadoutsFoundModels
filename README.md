# Topological Readouts for Biological Foundation Models


In recent years foundation models for natural lanuage have come to prominence. They have been used to understand medical data as well [[1]](#1). 


Foundation models input a sequence of tokens $\vec{s}$ of length $n$ and outputs a point cloud of representations $\phi(s_1), \dots, \phi(s_n)$. These are usually pooled via e.g. mean aggregation into a final representation via $$\phi(\vec{s})=\frac{1}{n}\sum_{i=1}^n\phi(s_i)$$.

Our approach is to treat the collection $\{\phi(s_1), \dots, \phi(s_n)\}$ as a *point cloud* that can be analyzed with topological techniques. 

## References
<a id="1">[1]</a> 
Moor, Michael, et al. "Foundation models for generalist medical artificial intelligence." Nature 616.7956 (2023): 259-265.
