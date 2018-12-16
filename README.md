# PACAID by KHF
---

### Execution Flow

- Open PaCaidMain.py and update the parameters - file_path (path to the test images), patchSize, fileSaveExtension
- Execute the file - **_python PaCaidMain.py_**
- Output will be stored in a new folder located at the same base location as the input images. e.g if input folder is '/data/test', then output will be '/data/test_cleaned_ps_65' for a patch size of 65


### Filelist

- core/ - Contains the core network architecture
- extras/ - Code to generate train/test data set by adding spatially varying noise.
- weights/ - Stores the trained weight files
- data/ - COntains the training and testing image files
- PaCaidMain.py - The main code file. Run this to test out the algorithm.
- patchifier.py - Contains code to convert image to patches and back.

&nbsp;


### Required modules

- keras
- opencv-python
- numpy
- gc
- psutil


### Demo and Code

Code available at - [https://github.com/HarshSharma12/PACAID](https://github.com/HarshSharma12/PACAID)
Demo video is available at - [https://www.youtube.com/watch?v=RP04KRFilEg](https://www.youtube.com/watch?v=RP04KRFilEg)