# Furniture Classification Models
This is the Group Machine Learning Project for COSC2753 Machine Learning course - Semester 2024A by Team SG_T2_G3
Deep Learning Models: Building convolutional neural networks (CNN) using TensorFlow and Keras for image classification tasks.  
Model Evaluation: We employ fine tuning for Adam and SGD optimizer as well as Early Stopping function in order to evaluate and improve the performance of our models.  
Model Architecture  
Training:  
The model is trained using the training dataset with the objective of minimizing a categorical cross-entropy loss function. During training, the model's weights are adjusted iteratively using the Adam optimizer.  

Training Parameters  

For Self-build model:    
Batch Size: 32  
Image Size: 224 x 224  
Optimizer: Adam  
Number of Epochs: 5  
Learning Rate: 0.001  

For AlexNet model:    
Batch Size: 32  
Image size: 227 x 227  
Optimizer: SGB  
Learning Rate: 0.01  
Number of Epochs: 5  


*INSTRUCTIONS TO RUN THE JUPYTER NOTEBOOKS*
Step 1: Unzip this file and open the folder Tasks, it can be run on any IDE (ex. Visual Studio Code) or opened on any browser after launching JupyterLab through Anaconda.
Step 2: Each cell in these files is a block of code that has been executed. All results are already displayed, each cell can be run seperately again.
