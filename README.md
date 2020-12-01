<!-- ABOUT THE PROJECT -->
## Dissertation: Icon Generation with a Generative Adversarial Network Conditioned on class 

*	Built a Machine Learning algorithm that generates icons conditioned on class
* Implemented the program using PyTorch – a Python-based library
* Generated promising icons that can potentially be used in a design system library
* The project offered a first glance at how Artificial Intelligence can revolutionise the design industry by assisting the designers in the creative process 

### Built With

* [PyTorch](https://pytorch.org/)
* [Google Colab](https://colab.research.google.com/)
* [Jupyter Notebook](https://jupyter.org/)

<!-- GETTING STARTED -->
## Getting Started

The folder contains the cDCGAN.ipynb file which is the notebook where I did my work 
and a folder called Icons50. In the Icons50 folder there are two subfolders - Icons-50 and results. 
The 'Icons-50' folder is the dataset which consists of 10.000 icons structured in 50 different classes.
The 'results' folder contains the checkpoints saved during the training and the fake generated images.

### Libraries 

* numpy
* matplotlib
* pytorch and torchvision
* python 3.7.3

### Instructions to run/open the code

In order to open the notebook cDCGAN.ipynb, jupyter notebook is required to be installed along with a couple libraries which you can find in the section above.

After everything is installed, Jupyter Notebook can be opened from command prompt by writing "jupyter notebook". A window will pop-up in the browser and the notebook can be opened with the help of the jupyter file explorer.

If the project's training and functionality needs to be tested, the path to the dataroot (Icons-50) in cell [53] needs to be changed. Also, in cell [61] the 'save_dir' needs to be changed as well, or it will create automatically a 'results' directory. 

The system can either be trained or a checkpoint can be loaded. In order to train it, run all the cells, and on the last one cell just type in 'icon_gen.train()' and it will start training. To load a checkpoint from the 'checkpoints' folder, just type in 'icon_gen.load('add the path here as seen in the notebook').
