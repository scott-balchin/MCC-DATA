---
uid: P001
slug: left-proper
name: Left-Proper
---
A model structure on a cateogry $\mathcal{C}$ is _left-proper_ if for every weak equivalence $A \to B$, and cofibration $A \to C$, the map $f$ in the following pushout is also a weak equivalence:
$$
\xymatrix{
  A \ar[r]^{\in \mathcal{C}_\textbf{C} } \ar[d]_{\in \mathcal{W}_\textbf{C}} & C \ar[d]^f \\
		B \ar[r] &  \ar@{}[ul]|<<<{\text{\pigpenfont I}} P\rlap{ .}
}
$$
