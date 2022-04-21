# Controlling a Vehicle’s Steering Angle With Convolutional Neural Networks (CNN) and Udacity Simulator

This project develops a camera-based steering angle prediction with Keras and Udacity simulator.

![](https://github.com/xiamze/steering_angle_prediction/blob/main/Image/1.png)

## About The Project

Autonomous driving has been the most prevalent topic for years and also human’s ultimate imagination about cars. Among all technologies that comprise vehicle autonomy, computer vision plays a key role as it processes images with rich and direct information. Compared to other technologies like radar, which provides only limited surrounding information through complicated processing, computer vision offers methods to detect and model every image element in a stable, efficient way at lower cost. 

Along with our Neural Network topics, our team has made an easy attempt to enable vehicle autonomy with CNN and udacity simulator. First, we generate a training dataset by manually controlling the car and images taken by its virtual cameras will be saved. Then we load the images and saved steering angles into a data augmentation pipeline to produce data diversity; augmented data will come into CNN training in batches, and finally we obtain a model that could predict the steering angle with an input image. Specific details are as follows.

## Dependancies

Create an environment with [packages](https://github.com/xiamze/steering_angle_prediction/blob/main/environment.yml) (Anaconda recommended) by running the following command.

```
conda env create -f environment.yml 
```
If the code doesn't work, install manually by pip according to the .yml file.

