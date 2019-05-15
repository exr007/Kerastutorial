**SASP Keras Skill Session**

This is a tutorial for using some of the basic features in Keras. 

Requirements
- Python 3.6 or earlier (Tensorflow may/may not work with 3.7, it does for Warrick but it doesn't for me)
- tensorflow
- keras
- numpy
- matplotlib
- jupyter notebook

Preparation
Since we'll be needing Python 3.6 for this exercise it's probably easiest to create a fresh virtual environment and then install everything in there. 

I personally use Conda, since it makes  handling environments as well as installing the few extra libraries we'll need much simpler. Otherwise everything should be pip installable too. 

If you are using Conda, do the following to create a virtual environment with all the required libraries installed:
- $ conda create --name myenv python=3.6 anaconda keras jupyter
- $ source activate myenv

To deactivate and remove the virtual environment just do:
- $ source deactive
- $ conda remove --name myenv --all
