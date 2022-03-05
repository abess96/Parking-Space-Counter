# Parking-Space-Counter

The project is about checking whether parking space are available or not. Also, we count the number of vacant and occupied spaces.


## Installation

1. Download the repository.
2. Install dependencies OpenCV and CVZone
3. Fire up a terminal inside the repo and run python main.py


## Approach

Our approach is purely based on traditional computer vision techniques, sometimes simple approaches outperform deep learning techniques
1. First of all we are defining the no of parking spaces in the parking garage and saving them in pickle format
2. Then checking pixel intensity in each lot thereby we can find a threshold to distinguish whether the car is present or not
