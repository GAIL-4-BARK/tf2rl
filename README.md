# TF2RL
TF2RL is a deep reinforcement learning library that implements various deep reinforcement learning algorithms using TensorFlow 2.0.

## Algorithms
Following algorithms are supported:
- DQN
- DDPG
- TD3
- ApeX (DDPG or TD3)

## Installation
```bash
$ git clone https://github.com/keiohta/tf2rl.git tf2rl
$ cd tf2rl
$ pip install -U numpy pip
$ pip install .
```

If you want to run example codes, you need `pip install .[examples]`
which install additional dependencies.

If you are developer, set `-e` option, then local modification affects
your installation.

## Example
- Train DDPG agent
  - If you want to train with only CPU, set `--gpu -1`

```bash
$ cd examples # You must change directory to avoid importing local files.
$ python run_ddpg.py --gpu -1
```
