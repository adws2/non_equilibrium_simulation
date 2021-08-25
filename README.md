통계물리학 시뮬레이션,

1. 이차원 이징모델
  Metropolis algorithm 사용.  
  로컬계산만 이용해서 transition probability p(-dE/t)를 구한다.  
  Order parameter $m = < s >$ 를 계산하여 paramagnetism -> ferromanetism phase transition 을 볼 수 있다.  
  <조금 더 구체적 분석 필요>  
  
2. 연속시간 무작위걸음  
  time distribution function 을 input 으로 받고, time 마다 무작위 걸음을 한다.  
  <harmonic potential 경우 기존 답과 틀리다 -> 수정필>  
    
3. 모래쌓기모델  
  2차원 격자위에 모래알을 한 알씩 떨어뜨린다.  
  모래알이 같은 지점에 4알이 될때, avalanche 가 일어 난다.  
  avalanche 규모의 분포를 보면 power law.  
  <avalanche distribution log binning 추가필요>  
  
4. 스몰월드 네트워크모델  
  regular network 를 만들고 rewiring 을 한다.  
  rewiring = 0  : regular (ordered : clustering coefficent is large and shortest path length is large too)  
  rewiring = 1  : random (disordered : '' is small and '' is small too)  
  Therefore, there is a phase transition.  
  In the context of network, small world network is defined that clustering coefficient is large but shortest path length is small.  
