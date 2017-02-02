# RegionGrowingAlgorithm

1. This algorithm is used to used for region segmentation based on user-choosen seed pixels.
2. This [paper](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.59.8092&rep=rep1&type=pdf) describes the method presented in the code.
3. Please cite the usage of this algorithm to the authors.

## Requirements

1. This module needs Python 2.x, [Numpy](http://www.scipy.org/scipylib/download.html), [SciPy](http://www.scipy.org/scipylib/download.html), [datetime](https://docs.python.org/2/library/datetime.html), [ast](https://docs.python.org/2/library/ast.html)

## Citations

*Vezhnevets, Vladimir, and Vadim Konouchine. "GrowCut: Interactive multi-label ND image segmentation by cellular automata." proc. of Graphicon. Vol. 1. 2005.* 

## Usage


1. `python main.py sample/star-white-clipart.jpg [[300,300]]` reads the file sample from sample folder with one pixel as seed at [300,300]
