The code for this project is created based on the donkeycar open-source library.
https://github.com/wroscoe/donkey/

This repo includes the code that lives on the PC to train the data using a 2D CNN model, 
then sync it back to the car when done. 
The code for the raspberry pi on the car can be found on this repo: 
https://github.com/ryannguyen94/CUDA_project

Things that are modified/added to fit our design:
  - The machine learning algoritm:
      . 2D convolution neural network layer structure
      . The batch size

manage.py is the main script that can be used to run training, manual driving, or autopilot driving.
Because this code lives on the PC, to run training, type in the cmd line:
python manage.py train --tub <data folder> --model <path to where the model can be save>
