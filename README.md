[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/QM7QGF1q)
# Isomorphism

Prove that if two graphs $A$ and $B$ are isomorphic they do *not* have to
be completely connected. I have started with the formal definition of
isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

Objective

Show that isomorphic graphs $( G_1 )$ and $( G_2 )$ do not have to be completely connected. We will prove this by a counterexample.

Counterexample

Consider graphs $( G_1 )$ and $( G_2 )$ each containing three vertices, defined as follows:

- $( G_1 = (V_1, E_1) )$ where $( V_1 = {v_1, v_2, v_3\} )$ and $( E_1 = {(v_1, v_2), (v_2, v_3)} )$.
