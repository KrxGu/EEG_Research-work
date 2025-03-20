chrononet: CNN-LSTM network +GRU Layers

paper referance for pytorch implementation https://arxiv.org/abs/1802.00308

Figure 2b-Proposed ChronoNet architecture
which includes both multiple filters of exponentially varying lengths in the 1D convolution layers and
dense connections within the GRU layers.

![image](https://github.com/user-attachments/assets/2b0eebea-66b2-4d82-853d-eb2dca74a4b4)

Dataset: https://data.mendeley.com/datasets/fshy54ypyh/2

note that the above data set is in .mat format hence need to be converted to mne format

paper implementing the above dataset: https://ieeexplore.ieee.org/document/9244283

implementing CNN-RNN
