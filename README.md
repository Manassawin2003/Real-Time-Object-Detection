SET UP cmd 

Step 1.Clone this repository: https://github.com/nicknochnack/TFODCourse

Step 2. Step 2. Create a new virtual environment

python -m venv tfod
            
Step3.Activate Env

                                  WINDOW 11

cd C:\Tensorflow Object Detection\TFODCourse    # Set destination to our project
.\tfod\Scripts\activate       # Activate the environment


                              WSL2-Linux

cd /mnt/c/Tensorflow\ Object\ Detection/TFODCourse      # Set destination to our project
source tfod2/bin/activate      # Activate the environment

Step 4. Install dependencies and add virtual environment to the Python Kernel
1.python -m pip install --upgrade pip
2.pip install ipykernel
3.python -m ipykernel install --user --name=tfod


Step5.After activate environment  type " Jupyter Notebook " to open the code

Step6.Do the Image Collection first then Training and Detection

After That Run The code step by step. If it Error or can't find a Modules, Go download it.

                               See The Statistics of our Train and Evaluate

                # Set destination to our last checkpoint ( to train and evaluate folders )
C:\Tensorflow Object Detection\TFODCourse\Tensorflow\workspace\models\my_ssd_mobnet

                # Open Tensorboard to see the result
tensorboard --logdir=.                                                                                                           
