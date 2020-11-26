# Off-Policy Deep Reinforcement Learning without Exploration (REM + TD3)

**Note this is a preliminary repository and not much effort was spent getting REM to work well with TD3 and should only be used a starting point for MuJoCo experiments.**


If you use this code, please cite the [paper](https://arxiv.org/abs/1812.02900) and the [paper](https://arxiv.org/abs/1907.04543). To launch batch experiments with `RSEM` or `REM`, use the file `run_main.sh`. To generate data, use `run_expert.sh`. The `DDPG_REM` agent doesn't work, while `RSEM` works (not well though). 

Method is tested on [MuJoCo](http://www.mujoco.org/) continuous control tasks in [OpenAI gym](https://github.com/openai/gym). 
Networks are trained using [PyTorch 0.4](https://github.com/pytorch/pytorch) and Python 2.7. 
