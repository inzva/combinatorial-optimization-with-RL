## inzva AI Projects #3 - Solving Combinatorial Optimization Problems with RL


Combinatorial optimization problems, a famous example of which is the Traveling Salesman Problem, are often solved with hand-crafted
algorithms that are often costly to develop and difficult generalize. With this project, we investigate how state-of-the-art models can be
trained to learn such heuristics automatically via reinforcement learning, and propose additional tweaks to improve its performance.

#### Contributors

- Furkan Gürsoy - [furkangursoy.github.io](http://furkangursoy.github.io)

- Batuhan Koyuncu - [bkoyuncu.github.io](http://bkoyuncu.github.io)

\**Both contributed equally.*

\*\**We also thank Sercan Amaç for his contributions.*


### More information

0. COwRL.pdf file contains the slides describing the problem and the performed analysis.

1. To train models using different distributions, you can replace the content of attention-learn-to-route/problems/tsp/problem_tsp.py file with the contents of problem_tsp_normal.py and problem_tsp_exp.py for normal and exponential distributions respectively.

2. pretrained_novel folder contains models trained with data from different distributions rather than the uniform distribution utilied in the original work.

3. TSP20_Experiments.ipynb and TSP50_Experiments.ipynb are two standalone notebooks for evaluating performance results of existing and novel pretrained models, and baselines on data from different distributions.


*Feel free to open issues or contact us.*
