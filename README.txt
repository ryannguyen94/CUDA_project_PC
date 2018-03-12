The code project is created based on the donkeycar open-source project.
https://github.com/wroscoe/donkey/

This repo includes the code that lives on the PC to training data, product the model and sync it back to the car. The code for the raspberry pi on the car can be found on this repo: https://github.com/ryannguyen94/CUDA_project

Things that are modified/added to fit our design:
  The machine learning algoritm:
    2D convolution neural network layer structure
    The batch size
  The data rate
  The PWM range of throttle and steering
  The addition of throttle deadzone in the control of the throttle
  The camera resolution
  The image filter was added but is commented out because it slowed down the process too much
