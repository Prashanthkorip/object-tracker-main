# Object Tracking using Optical Flow
This is the high level code implemented for term project of class CMPE 297 - Special Topics Spring 2024 at San Jose State University, under Professor Jun Liu

- The project is about Object Tracking using Optical Flow

- The code is implemented in PyTorch.
- Most of the code is in notebooks, all ablations, tests and final code exists there.
- All the inference is done on Nvidia V100 of SJSU Coe HPC.
- Model weights and subsequent evaluation data initially are stored in HPC `/scratch/cmpe297-sp24/` folder of both folder `agflow` and `sam-weights`

# For running the code
- `notebooks/final_inference.ipynb` has the final code for demoing our solution
- `notebooks/inference_cotracker.ipynb` and `notebooks/inference.ipynb` has our raw working code, all the ablations we tried out
- :warning: Make sure you have access to HPC as the computations are expensive

# Credits
Uses https://arxiv.org/abs/2202.03857 Learning Optical Flow with Adaptive Graph Reasoning 

Uses https://github.com/facebookresearch/co-tracker CoTracker

# Authors

Saish Reddy Komalla (saishreddy.komalla@sjsu.edu)

Prashanth Sai Santosh Koripalli (prashanthsaisantosh.koripalli@sjsu.edu)
