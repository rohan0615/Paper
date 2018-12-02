This program is used to train ETH-CNN at the All-Intra configuration. Among all the four Python files, "train_CNN_CTU64.py" is the main file that can be run directly. Following are running steps.

(1) Make sure the training/validation/test data are stored in folder "Data/". The folder name and file names are set in "input_data.py". We are regret to tell that the whole data for reproducing our ETH-CNN based approach are so large, and for brevity, only a random part of data are provided currently for demo use.  

(2) Edit "input_data.py" to select QP range, and edit "train_CNN_CTU64.py" to set running mode (train/evaluate), iteration times, learning rate with decay ratio, and whether to reload the model. All above settings can be found by following the comments. 

(3) Run "train_CNN_CTU64.py", and the loss/accuracy on the training/validation sets are periodically printed in the console. 

(4) After training completes, path into folder "Model/", and you will find the trained model with corresponding data files, including TXT files recording loss/accuracy and PNG files plotting the curves.

Note: Without any editing, the program can also be directly executed, where ETH-CNN will be trained for QP 20~25 by default.
