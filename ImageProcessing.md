Broadly speaking, the image processing in EDGE is done with a bandpass filter and then a threshold, followed by a series morphological operations to clean up the images. More details on how the image processing works can be found in the [Supporting Information](http://people.seas.harvard.edu/~mgelbart/publications/Gelbart2012_SI.pdf) section of our [publication on EDGE](http://people.seas.harvard.edu/~mgelbart/publications/Gelbart2012.pdf).

If you are interested in seeing the image processing code directly, [download](http://code.google.com/p/embryo-development-geometry-explorer/downloads/list) EDGE and you will find it in `<EDGE_install_directory>/Matlab/get_membs_v3.m`.