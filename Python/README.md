# Installation Instructions
## From Source code
***

- Step 1:  Have CUDA 11.3 or higher installed on your OS
- Step 2: Create a Conda Virtual Environment with Python 3.7
- Step 3:
```python
# Install cudatoolkit and cudnn library using conda
conda install cudatoolkit=11.3.1 
conda install cudnn=8.2.1 
```
- Step 4: 
```python 
git clone https://github.com/tensorlayer/hyperpose.git 
```
- Step 5: Replace the ```requirements.txt``` file's content with the following:
```txt
cython>=0.29
numpy==1.19.4
easydict>=1.9,<=1.10
opencv-python>=3.4,<3.5
tensorflow==2.5.0
tensorlayer==2.2.3
pycocotools==2.0.0  # must be installed after cython and numpy are installed

# matplotlib==3.5.2
# pip install tqdm
```
- Step 6:
```bash
pip install -U -r hyperpose/requirements.txt
```
- Step 7: Test yout installation by checking if there are GPU devices detected:
```python
import tensorflow as tf
tf.test.is_gpu_available()
# should return True
```
