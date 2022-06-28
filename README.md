# VISIOPE-CNN-OCR

## OCR for Handwritten Data

### Introduction to Project
This project is aiming to build an OCR system, employing Convolutional neural network models on the EMNIST dataset. The aim of the project is to design and implement a neural network model that is efficient at reading texts handwritten by humans and can be used in multiple applications in the future such as Real-time Translation, pdf readers, digitalizing ancient books, and many more.

### Pre-Requisites
To run the project, you need to have the following tools installed:
* Anaconda Jupyter Notebook / Google Colab (recommended)
* Python 3.2 or above

### Technology and Tools Used
* Pytorch Framework v1.10
* Google Colab with GPU
* Scikit Learn
* Matplot
* Numpy

### Dataset Information
The data used to train and test the neural network for OCR is the widely known EMNIST dataset. This dataset extends the previously established MNIST data with handwritten character digits. These are derived from the NIST Special Database 19 and converted to 28x28 pixel images to match the MNIST dataset. More details can be found [here](https://www.nist.gov/itl/products-and-services/emnist-dataset).

### Project Execution Guideline for Google colab
1. Open the Project Deep Learning.ipynb in Google Colab.
2. Click on the file's icon
3. In sample data, right-click and click on Upload.
4. Upload the following 2 folders from the Project file.
    * CroppedHandwritten
    * Letters
5. Right-click on the “CroppedHandwritten” folder and click on copy path.
6. Go to section “Test 2 “ and paste the copied path in the folderpath variable.
7. Similarly, right-click on the “Letters” folder and click on copy path.
8. Go to section “Test 3” and paste the copied path in folderpath variable.
9. Run the code to view the results

** Note: Please make sure you have properly followed the above lines and paste the right path for the folders in order for the code to run.**

### Acknowledgments
1. EMNIST Dataset Repository
2. Kaggle EMNIST Code Notebooks and Discussion
3. Useful Notebook for Architecture of CNN
4. MNIST Example Notebook
5. Useful resource for loading EMNIST data
6. Tkinter Useful sample for Beginners.

### Credits
The project is developed by the following students as part of the Computer Vision & Perception course
at Sapienza University for Academic Year 2022-23.
* Sandesh Kumar
* Faisal Gul
