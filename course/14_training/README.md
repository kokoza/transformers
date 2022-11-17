**The following notebooks had errors running on my machine.**

* 03_mlm_training.ipynb
* 04_mlm_training_Trainer.ipynb
* 06_nsp_training.ipynb
* 08_mlm_and_nsp_training.ipynb

May need to ensure the proper versions of the following packages.

* tensorflow <!-- 2.9.2 (installed with pip) -->
* cuda <!-- 11.5.1 (installed with sudo apt install nvidia-cuda-toolkit) -->
* cudnn <!-- 8.2.4.15 (apparently for cuda 11.4, installed with sudo apt install nvidia-cudnn) -->
* nvidia-driver-510 <!-- (installed with sudo apt install nvidia-driver-510 after installing cuda and cudnn) -->
reboot

 See [TensorFlow 2.10 causes trouble!](https://github.com/google-research/multinerf/issues/47) issue on Github.
