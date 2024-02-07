### Representaion Learning
- 개념, 지식 주어진 환경을 어떻게 표상해야 세상을 이해 할 수 있는가?
- Epistemic forgaging (세상 파악하기)
- Exploration(탐험)
- Perception (지각)

### Value Learning 
- (외/내재적) 가치를 가지고 있는 목표를 달성하기 위해 어떻게 행동을 선택할 것인가?
- Pragmatic reward foraging (보상 획득하기)
- Exploitation(활용)
- Action policy (행동 정책)

### 체화된 인지

### 강화학습의 성공
- deepmind
- Open AI : Hide and seek, self play
- 강화학습의 대중화 : 한글, 혁펜하임

### Moravec's paradox


### 강화학습은 무엇인가?
- 강화학습의 중요한 특징들은 무엇인가?
    1. 강화
    1. 보상(답이 아니라 시간 지연)
    1. 스스로 하는 학습
    1. learning what to do = mapping situations to actions
    1. goal: maximize a numerical reward signal
    1. No direct answer is given : trial-and-error(evaluation) search and <b>delayed reward</b>
    1. <b>Subsequent rewards</b>
- Reinforcement Learning 2nd edition, Richard S. Sutton and Andrew G. Barto
- RL = Search + Memory
- 최적 제어와 다른점
- 기억, 지각, 주의 등과의 관계

### Supervised learning, Unsupervised learning과 차이점
### 정책, 보상 신호, 가치 함수, 모델
- Learning with a critic

### 지각, 기억, 주의
1. 정책(policy) : 주어진 시점에서 에이전트의 행동방식: mapping states to actions
1. 보상 신호(reward signal) : 각 시점에 환경이 에이전트에게 보내는 하나의 숫자, 강화학습의 목표는 오랜 시간동안 총 보상의 양이 최대로 만드는 것, 보상 신호는 즉작적인 외부 신호!
1. 가치 함수 (value function) : 장기적으로 볼 때 무엇이 좋은 것인지에 대한 것.
1. 모델(model) : 환경이 어떻게 변화하는지에 대한 것을 반영하는 것, 세상에 대한 모델

### 가치 함수
1. 전체를 다 모른다는 것(limited information)
1. 세상이 변할 수 있다는 것(nonstationary)
1. 세상이 확률적이라는 것(stochastic)