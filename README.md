# 통계물리학 시뮬레이션,

### 1. 2D Ising model using Metropolis algorithm[1]  
1. Calculate transition probability p(-dE/t)  
2. Obtain spin configuration samples.  
3. Calculate the magnetization m, to find phase transition.  
- The magnetization m of the 2D Ising model  
![magnetization](2D Ising model/save/magnetization.svg)

  
### 2. CTRW(Continuous-time random walk)  
INPUT : time/step-lengths distribution / OUTPUT : random walk trajectory  
If step-lengths distribution is Levy distribution, position random variables are distributed power-law.  
- Histogram of Levy flight
![Levyflight](CTRW/save/Levy.svg)


### 3. Sandpile model[2]
1. Drop a grain of sand onto a random position of two-dimensional lattice.
2. Repeat 1 until there are four sand in the same position.
3. The four grains of sand collapse and pass them to the surrounding area. 
- Result : Avalanche size distirbution is the power-law.  
  
### 4. Small world netwrok[3]  
- Create regular network and rewire a random node.
  rewiring = 0  : regular (ordered : clustering coefficent is large and shortest path length is large too)  
  rewiring = 1  : random (disordered : '' is small and '' is small too)  
  Therefore, there is a phase transition.  
  In the context of network, small world network is defined that clustering coefficient is large but shortest path length is small.  
![smallworld](Smallworld network/save/clustering.svg)

### Reference
- [1] M.  E.  J.  Newman  and  G.  T.  Barkema. Monte Carlo methods in statistical physics. Clarendon Press, Oxford, 1999.
- [2] Christensen, Kim, and Nicholas R. Moloney. Complexity and criticality. World Scientific Publishing Company, 2005.
- [3] Newman, Mark EJ, Cristopher Moore, and Duncan J. Watts. Mean-field solution of the small-world network model. Physical Review Letters 84.14, 2000.
