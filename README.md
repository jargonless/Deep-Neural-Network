In this class project, we revisited H M Dipu Kabir, Abbas Khosravi, and Saeid
Nahavandi’s paper “SpinalNet: Deep Neural Network with Gradual Input.” and attempted to reproduce a subset of their key findings.
The paper and authors' code can be found here: https://paperswithcode.com/paper/spinalnet-deep-neural-network-with-gradual-1

1. Our code requires pytorch and torchvision.

2. In order to reproduce our result, please execute the file named "CNN_vs_SpinalFC.py"

3. The CNN and SpinalFC use ReLu as activation function. To replicate our experiment regarding different
activation functions, please use the other 2 files named "CNN_vs_SpinalFC_Tanh.py" and "CNN_vs_SpinalFC_Sigmoid.py".

4. As for ablation and dropout experiment, please see the comments to change parameters in the file "CNN_vs_SpinalFC.py".
