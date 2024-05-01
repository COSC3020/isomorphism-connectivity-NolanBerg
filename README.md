[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/QM7QGF1q)
# Isomorphism

Prove that if two graphs $A$ and $B$ are isomorphic they do *not* have to
be completely connected. I have started with the formal definition of
isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

Sources: Used google for this assignment

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

Objective

Show that isomorphic graphs $( G_1 )$ and $( G_2 )$ do not have to be completely connected. We will prove this by a counterexample.

Counterexample

Consider graphs $( G_1 )$ and $( G_2 )$ each containing three vertices, defined as follows:

- $( G_1 = (V_1, E_1) )$ where $( V_1 = {v_1, v_2, v_3\} )$ and $( E_1 = {(v_1, v_2), (v_2, v_3)} )$.

- $( G_2 = (V_2, E_2) )$ where $( V_2 = {w_1, w_2, w_3} )$ and $( E_2 = {(w_1, w_2), (w_2, w_3)} )$.

Bijection $( f )$:

Define $( f: V_1 \rightarrow V_2 )$ by mapping $( f(v_1) = w_1 )$, $( f(v_2) = w_2 )$, and $( f(v_3) = w_3 )$.

Adjacency Preservation:

- $( v_1 )$ is adjacent to $( v_2 )$ in $( G_1 )$, and $( f(v_1) = w_1 )$ is adjacent to $( f(v_2) = w_2 )$ in $( G_2 )$.

- $( v_2 )$ is adjacent to $( v_3 )$ in $( G_1 )$, and $( f(v_2) = w_2 )$ is adjacent to $( f(v_3) = w_3 )$ in $( G_2 )$.

- $( v_1 )$ is not adjacent to $( v_3 )$ in $( G_1 )$, and $( f(v_1) = w_1 )$ is not adjacent to $( f(v_3) = w_3 )$ in $( G_2 )$.

Since all adjacency relations are preserved by bijection $( f )$, and $( (u,v) \in E_1 )$ iff $( (f(u),f(v)) \in E_2 )$, the graphs $( G_1 )$ and $( G_2 )$ are isomorphic.

Analysis

Neither $( G_1 )$ nor $( G_2 )$ is a complete graph because there are pairs of vertices in each graph that do not have an edge between them (e.g., $( v_1 )$ and $( v_3 )$ in $( G_1 )$, and $( w_1 )$ and $( w_3 )$ in $( G_2 )$).


