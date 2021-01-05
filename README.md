# NDT_ML_Flaw
This is a data set for teaching a machine learning learning model with different types of flaws. The data is zipped in an .xz format, which can be opened for example with Python LZMA package. The data size is 480x7168 and the flaw area 1100-3100. Each file contains 1000 images with roughly 50% flaws and 50% no flaws.

The .xz files contain the actual images and .txt files metadata regarding the image.
Metadata example
Flaw (1 flaw, 0 no flaw), Amount of augmentation (between 0.4-1), Flaw depth  Flaw location (scan axis)  Original flaw size, index line (always one), Flaw type
1	                        0.472899	                              1681.461469	210.526275	               2.0	              1	                         P41_01

