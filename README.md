# clij2-fft: Fast GPU FFT based image processing algorithms for everybody

The goal of clij2-fft is to provide the bio-imaging community with fast but simple to use implementations of 2D and 3D FFT and FFT based algorithms (such as convolution and deconvolution). 

Latest features and updates are tracked in the [Release Log](https://clij.github.io/clij2-fft/docs/releaselog)

The clij2-fft project is built upon [clFFT](https://github.com/arrayfire/clFFT)  

## Java and ImageJ

clij2-fft is shipped as part of [clij2](https://clij.github.io).  Follow [these instructions](https://clij.github.io/clij2-docs/installationInFiji) to install clij2. You can then access Richardson Lucy Deconvolution via the CLIJ2-assistant as shown in [this video](https://clij.github.io/clij2-fft/docs/deconvolution/clij-decon.mp4).

To build the code follow [these instructions](https://clij.github.io/clij2-fft/docs/buildlibs/build)

Currently clij2-fft is a work in progress.  The best way to learn how to use clij2-fft is to study the examples then follow up with questions on the [Image.sc Forum](https://forum.image.sc/).   

If you are a java programmer the clij2-fft test [here](https://github.com/clij/clij2-fft/tree/master/src/test/java/net/haesleinhuepf/clijx/tests) may be helpful.   

If you are a script programmer these [scripting examples](https://github.com/clij/clij2-fft/tree/master/src/main/jython) may be helpful.  

## Python

If you are a python programmer take a look at the ```python``` sub-directory for the experimental python distribution.  See [these installation instructions](https://github.com/clij/clij2-fft/blob/master/docs/python/clij-fft-python.md) and also this [python example](https://github.com/clij/clij2-fft/tree/master/python/clij2fft/test_richardson_lucy.py) may be helpful.  

Please note thus far only a small subset of potential algorithms have been implemented.  For example we have implemented 3D deconvolution but not 2D, and 2D FFT but not 3D.  If you are in need of a particular FFT flavor, or FFT based algorithm, please ask questions on the forum.  We can prioritize future work based on that feedback and also help others implement additional algorithms. 
