# deepNF
This repository contains Python scripts for "deepNF: Deep network fusion for protein function prediction" by V. Gligorijevic, M. Barot and R. Bonneau.


# Citing
```
@article {Gligorijevic2017,
	author = {Gligorijevi{\'c}, Vladimir and Barot, Meet and Bonneau, Richard},
	title = {deepNF: Deep network fusion for protein function prediction},
	year = {2017},
	doi = {10.1101/223339},
	publisher = {Cold Spring Harbor Laboratory},
	URL = {https://www.biorxiv.org/content/early/2017/11/22/223339},
	journal = {bioRxiv}
}
```
## Usage
To run *deepNF* run the following command from the project directory:
```
python2.7.py main.py example_params.txt
```
## Dependencies

*deepNF* is tested to work under Python 2.7.

The required dependencies for OhmNet are [Keras](https://keras.io/), [TensorFlow](https://www.tensorflow.org/), [Numpy](http://www.numpy.org/), and [scikit-learn](http://scikit-learn.org/)
