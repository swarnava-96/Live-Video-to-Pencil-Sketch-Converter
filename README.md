# Live-Video-to-Pencil-Sketch-Converter

### Goal: The goal of this project is to select a certain portion of the face and create a rectangle box with the mouse using live webcam. The model will return the pencil sketched ROI using OpenCV.

### Brief Description:
I have used OpenCV and in this project. 

Firstly, I have initialized a function that will take an image as an input, converting it into gray scale, and it will use cv2 Gaussian Blur for creating the sketch ROI.
Then, I have defined rectangular box sizes for selecting the region of interests and converting for 3 channels to put back on original image (streaming), replacing the sketched image on Region of Interest.

### Demo:

### Installation:
The Code is written in Python 3.7.3 If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:

##### 1. First create a virtual environment by using this command:
```bash
conda create -n myenv python=3.7
```
##### 2. Activate the environment using the below command:
```bash
conda activate myenv
```
##### 3. Then install all the packages by using the following command
```bash
pip install -r requirements.txt
```
##### 4. Open the .ipynb file inside Jupyter Notebook and run the cells.

##### Make sure to change the directory to the root folder. The folder structure should be same as of this repository otherwise it will throw error. 
