---
title: Linear Algebra Basis Vectors
layout: page
---
$$
\newcommand{\ihat}{\hat{\boldsymbol{\imath}}}
\newcommand{\jhat}{\hat{\boldsymbol{\jmath}}}
\newcommand{\khat}{\hat{\boldsymbol{k}}}
\newcommand{\vc}[1]{\mathbf{#1}}
$$

* This will become a table of contents (this text will be scraped).
{:toc}

# Basis Vectors

Basis vectors are often referred to as $ \vc{e_1}, \vc{e_2}, \vc{e_3} $, etc. This notation is convenient because the subscript can become a variable, such as in: $ \vc{e_i} $.

The $ \ihat $, $ \jhat $ and $ \khat $ vectors are called the standard basis vectors for $ \mathbb{R}3 $.
They are the vectors $ \begin{pmatrix} 1 \\ 0 \\ 0 \end{pmatrix} $, $ \begin{pmatrix} 0 \\ 1 \\ 0 \end{pmatrix} $ and $ \begin{pmatrix} 0 \\ 0 \\ 1 \end{pmatrix} $ respectively. Notice also that they are the columns of the 3 x 3 identity matrix:
$$
\begin{bmatrix}
1 & 0 & 0 \\ 
0 & 1 & 0 \\ 
0 & 0 & 1 \\ 
\end{bmatrix}
$$

So the vector $ \begin{pmatrix} 3 \\ 4 \\ −2 \end{pmatrix} $ can be decomposed into the standard basis vectors like so:

$$
\begin{pmatrix} 3 \\ 4 \\ −2 \end{pmatrix} = 3 \begin{pmatrix} 1 \\ 0 \\ 0 \end{pmatrix} + 4 \begin{pmatrix} 0 \\ 1 \\ 0 \end{pmatrix} - 2 \begin{pmatrix} 0 \\ 0 \\ 1 \end{pmatrix}
= 3 \ihat + 4\jhat-2\khat
$$

We are not obliged to use this particular basis to express our vector, but this basis is certainly the most convenient. We may express our vectors using another basis of three vectors if needed. For example, if we let $ \vec{u} = \begin{pmatrix} 1 \\ 1 \\ 1 \end{pmatrix} $, $ \vec{v} = \begin{pmatrix} 2 \\ 1 \\ 0 \end{pmatrix} $, and $ \vec{w} = \begin{pmatrix} 0 \\ -1 \\ 1 \end{pmatrix} $ then

$$
\begin{pmatrix} 3 \\ 4 \\ −2 \end{pmatrix} = \frac{1}{3} \vec{u} + \frac{4}{3} \vec{v}-\frac{7}{3}\vec{w}
$$

Indeed, an interesting idea is to perform a change of basis. This is where matrices come into play.

https://www.clear.rice.edu/comp360/lectures/old/VectorGeomCordFree.pdf
