## inzva AI Projects #3 - Solving Combinatorial Optimization Problems with RL


Combinatorial optimization problems, a famous example of which is the Traveling Salesman Problem, are often solved with hand-crafted
algorithms that are often costly to develop and difficult generalize. With this project, we investigate how state-of-the-art models can be
trained to learn such heuristics automatically via reinforcement learning, and propose additional tweaks to improve its performance.

#### Contributors

- Batuhan Koyuncu 
- Furkan Gürsoy - [furkangursoy.github.io](http://furkangursoy.github.io)

*We also thank Sercan Amaç for his contribution.


###

1. To train models using different distributions, ...

2. pretrained_novel folder contains models trained with data from different distributions rather than the uniform distribution utilied in the original work.

3. TSP20_Experiments.ipynb and TSP50_Experiments.ipynb are two standalone notebooks for evaluating performance results of existing and novel pretrained models, and baselines on data from different distributions.
