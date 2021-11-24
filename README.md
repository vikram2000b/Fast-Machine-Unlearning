# Fast-Machine-Unlearning

The procedure for unlearning is presented in notebook. The code requires following packages to be installed:
1. PyTorch >= 1.5.0
2. TorchVision >= 0.2.2
3. Numpy >= 1.21.3

All the dependencies can be installed using envirnment.yml file.
The conda envirnment with the dependencies can be created using the following command:

```conda env create -f environment.yml```

The command will create envirnment named "Unlearning_Env". Activate the envirnment using

```conda activate Unlearning_Env```

The code can be used from notebook after activating the envirnment from conda.

If conda is not installed in system, the depedencies could be installed using pip, run following commands to install dependencies using pip:

```pip install torch==1.5.0 torchvision==0.2.2```

```pip install numpy==1.21.3```
