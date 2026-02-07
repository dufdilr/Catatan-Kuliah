#Definisi 

Misalkan $G$ suatu graf dan $V_1 \subseteq V(G)$ serta $E_1 \subseteq E(G)$. Didefinisikan
$$
G[V_{1}] := (V_{1}, K, \phi_{K})
$$
dimana $K := \{ e \in E(G) \ | \ \exists v \in V_{1}: v \in e\}$ dan $\phi_K(e) = \phi(e)$  untuk setiap $e \in K$

Didefinisikan pula
$$
G[E_{1}] := (L, E_{1}, \phi_{E_{1}})
$$
dimana $L := \{ v \in V(G) \ | \ \exists e \in E_{1}: v \in e\}$ dan $\phi_{E_{1}}(e) = \phi(e)$  untuk setiap $e \in E_{1}$


***
## Definition Used
* [[Subgraf]]