# Generalized Population-Based Training With Pairwise Learning (GPBT-PL)

Code for the Generalized Population-Based Training With Pairwise Learning (GPBT-PL) algorithm, from the paper *Generalized Population-Based Training for
Hyperparameter Optimization in Reinforcement Learning*.

The GPBT framework is implemented based on [ray](https://docs.ray.io/en/latest/ray-overview/getting-started.html). Heavily inspired by ray tune PBT example, GPBT-PL is included in the ray.tune library, which is the official supported implementation.


### Running the code

To run the PPO experiment, use command:

    python run_ppo.py 

To run the IMPALA experiment, use command:

    python run_impala.py


### Citing GPBT-PL

    @article{bai2024generalized,
      title={Generalized Population-Based Training for Hyperparameter Optimization in Reinforcement Learning}, 
      author={Hui Bai and Ran Cheng},
      journal={IEEE Transactions on Emerging Topics in Computational Intelligence},
      publisher = {IEEE},
      year={2024},
      doi={10.1109/TETCI.2024.3389777}
      }
