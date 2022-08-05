The repository contains supplemental files to the paper "On monochromatic arithmetic progressions in binary words associated with block-counting functions",
available at: https://arxiv.org/abs/2204.05287

Below is a brief description of the contents of the files:

1. longest_progressions.csv

The file contains the values $A_v(d)$ for all patterns $v$ such that $|v| \leq 3$ and all differences $d \in [1,2^{12}+1]$.
The first row consists of headings (corresponding to $v$), while the $(d+1)$ th row contains the values $A_v(d)$.

2. longest_progressions_from_0.csv

The file contains the values $A_v(0,d)$ for all patterns $v$ such that $|v| \leq 4, v \neq 0^i$ and all differences $d \in [1,2^{20}+1]$.
The first row consists of headings (corresponding to $v$), while the $(d+1)$ th row contains the values $A_v(0,d)$.

3. section_4_algorithm.nb

The file contains an implementation of the algorithm described in Section 4. 
The algorithm is then applied to the cases described in Lemma 4.8, yielding the results stated in the lemma.
