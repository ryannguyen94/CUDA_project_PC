The code project is created based on the donkeycar open-source project.
https://github.com/wroscoe/donkey/

Things that are modified/added to fit our design:
  The machine learning algoritm:
    2D convolution neural network layer structure
    The batch size
  The data rate
  The PWM range of throttle and steering
  The addition of throttle deadzone in the control of the throttle
  The camera resolution
  The image filter was added but is commented out because it slowed down the process too much
