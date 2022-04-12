# COMP-8610-RESK-RL-Research-Project
COMP-8610 RESK RL Research Project


run all cells of `ddpg_mt_car.ipynb`. This saves models and then run `render_from_checkpoint_car.py` to load and render form those checkpoints. It saves renders as GIF.


`1e3_adam_bn_199.gif` this refers to model with
- learning rate -> 1e-3
- optimizer -> adam
- regularization -> batch normalization
- last number suggests episode. "_199.GIF" means after 200 episodes, "_0.GIF" means before training.
