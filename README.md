# Theory-guided-Progressive-Transfer-Learning-Network-TPTLN-
Demo code release for TPTLN: Combining the theoretical bound and deep adversarial network for machinery open-set diagnosis transfer


## Dataset
### The Paderborn Bearing Dataset, Available: https://mb.uni-paderborn.de/kat/forschung/datacenter/bearing-datacenter
### The PHM 2009 Gearbox Dataset, Available: https://www.phmsociety.org/competition/PHM/09

## Requirements

- python 3.8
- torch 1.7.1+cu110
- torchvision 0.8.2+cu110
- Tensorflow  1.14.0
- Tensorlayer 1.14.0
- Tensorboard


## Training

- Step 1: Run the 'Building gearbox task.ipynb' or  'Building bearing task.ipynb' to preprocessing the dataset
- Step 2: Run the 'main.ipynb' to illustrate the proposed method
- Optional: The compared methods could be used for ablation study and performance comparison


## Reference codes
**https://github.com/thuml/easydl**

## Contact
- phoenixdyf@sjtu.edu.cn