# MNIST Dataset Decoder
Functions for decoding MNIST Dataset. 

### Usage
```python
import mnist_decoder as md
images = md.get_images("samples/train-images-idx3-ubyte.gz")  // <class 'numpy.ndarray'>
labels = md.get_labels("samples/train-labels-idx1-ubyte.gz")  // <class 'numpy.ndarray'>
```
