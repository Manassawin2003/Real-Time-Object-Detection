SET UP cmd By Manassawin

Step 1.Clone this repository: https://github.com/nicknochnack/TFODCourse

Step 2. Step 2. Create a new virtual environment
             python -m venv tfod


                                  WINDOW 11

cd C:\Tensorflow Object Detection\TFODCourse    # Set destination to our project
.\tfod\Scripts\activate                                              # Activate the environment


                              WSL2-Linux

cd /mnt/c/Tensorflow\ Object\ Detection/TFODCourse              # Set destination to our project
source tfod2/bin/activate                                                              # Activate the environment


After activate environment  type " Jupyter Notebook " to open the code

Do the Image Collection first then Training and Detection

After That Run The code step by step. If it Error or can't find a Modules, Go download it.

                               See The Statistics of our Train and Evaluate

                # Set destination to our last checkpoint ( to train and evaluate folders )
C:\Tensorflow Object Detection\TFODCourse\Tensorflow\workspace\models\my_ssd_mobnet

                # Open Tensorboard to see the result
tensorboard --logdir=.                                                                                                           
