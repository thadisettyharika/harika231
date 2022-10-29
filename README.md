Cooperative Exploration for Multi-Agent Deep Reinforcement Learning
ICML 2021
[Project Website] [PDF]
Iou-Jen Liu, Unnat Jain, Raymond A. Yeh, Alexander G. Schwing
University of Illinois at Urbana-Champaign

The repository contains Python implementation of Cooperative Exploration for Multi-Agent Deep Reinforcement Learning (CMAE) with Q-Learning on the discrete multi-agent particle environments (MPE).

If you used this code for your experiments or found it helpful, please consider citing the following paper:

@inproceedings{LiuICML2021,
  author = {I.-J. Liu and U. Jain and R.~A. Yeh and A.~G. Schwing},
  title = {{Cooperative Exploration for Multi-Agent Deep Reinforcement Learning}},
  booktitle = {Proc. ICML},
  year = {2021},
}
Platform and Dependencies:
Platform: Ubuntu 16.04
Conda 4.8.3
Python 3.6.3
Numpy 1.19.2
Training
cd script
sh run_came_push_box.sh
sh run_came_room.sh
sh run_came_secret_room.sh
Training log will be dumped to log/CMAE/.

License
CMAE is licensed under the MIT License

