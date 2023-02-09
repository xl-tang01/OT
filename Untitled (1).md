# Notes on optimal transport

## 1. Introduction to OT

### 1.1 What is OT

Optimal transport(OT) aims at finding a minimum cost/the most cost-effective transportation between two distributions $\mathbb P$ and $\mathbb Q$.  
OT problem seeks the most efficient way of transporting one distribution of mass into another.

<table>
<td> 
<img src="1x/Monge.png" style="width:350px;">
$$\textbf{Monge's Formulation}$$
</td> 
<td> 
<img src="1x/Kantor.png" style="width:350px;"> 
    $\textbf{Kantorovich's Formulation}$
</td> 
</table>
<caption><center> $\textbf{Figure 1}$: Diagrams of two kinds of optimal transport.</center></caption>

### 1.2 History

OT problem was first introduced by Gaspard Monge in 1781, which intends to use a pile of stones to build a military castle in a most efficient way. Its original formulation is written as
$\min_{T_{/#}\mathbb P=\mathbb Q}\int_{\mathcal X}c(x,T(x))d\mathbb P(x)$

