## Reinforcement Learning Engin
- Inputs : Camera 
- Model
- Outputs
- Rewards : 
- Navigate : 
- Cheats
- Test on Real Footage Calibrate camera
- Goal : Navigate from A to B in Carla with Traffic


## Carla Simulator
- "output-of-the-box" SB3 RL framework to Carla simulator
- PPO 
- 

## Reinforcement learning (RL skeleton)
- RL Env.
    - Action space(INPUT)
    - Reward(OUTPUT)
    - Observation Space(OUTPUT)
- Stable Baselines3 Algorithm
    - tries to figure out how to maximize reward given observations

- define class for enviroment
    - class CarEnv(gym.Env): 
        - init : connect simulator
        - step : define reward, if found episode end (collision), done
        - reset : spawn a car, attach sensors etc


## references

- https://www.youtube.com/@FullSimDriving
- https://github.com/vadim7s/SelfDrive.git