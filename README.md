# Algorithm 7
&1. $rs(KS_{N}) \subset  rsH_X \cup rsJ_{Z,A} \cup rsJ_{Z,C} \cup rsF_{Z}$   

&2. $rs(G_0) = (kerH_N)S_N \cap (rsH_N \oplus rsF_N)$   

&3. $rs(G_1) =  rs(J_{Z,A}S_{N}^T)$   

&4. For any $v_0 \in rsG_2$ , $v_0S_{N} = v_1v_2v_3$ , where $v_1 \in rsH_X$ ,  $v_2 \in rsJ_{Z,A}$ , $v_3 \in rsJ_{Z,C} - \{ 0 \}$  

&5. Let $G_2 \left(J_{X,C}S_{N}^T\right)^T = U$ and $U$ is full rank .  if $U$ is not full rank , there exist $g_{i}= v_{i1}v_{i2}v_{i3}$ and 
$g_{j}g_{k}= v_{m1}v_{m2}v_{i3}$ ,where $g_i$ is the i-th row of $G_2$ . But $G_1$ is full rank and noticing &4 , so $U$ is full rank .  
  
&6. Rewrite the matrix $G_2$ in the standard form through Gaussian elimination
*******
$$G_3 =\left( E_{k_N-q}\cdots \right) \pi \ \ \ and \ \ \ \pi \pi = E  $$ 
___________
&7. Output $D = \left( E_{k_N-q} \ 0 \right) (\pi)^T J_{X,C}S_{N}^T$. Noticing $G_2D^T \not= 0$
