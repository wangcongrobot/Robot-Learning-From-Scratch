# Robot-Learning-From-Scratch

Robot Learning is a challenging task. It is hard for a beginner to start the process of training a robot to learn skills from scratch. I will try to use some basic code to explain this procedure.

## Basics

You need some basic skills, such as C++/Python, Deep Learning, ROS, Robotics, Reinforcement Learning. 

The basic is a URDF robot model. We will transfer it from ROS to MuJoCo and train it with the PPO algorithm.


## [Modelling](/Modelling/README.md)

We show how to change the URDF model to MuJoCo xml model.

## [Task Define](/Task/README.md)

We define the OpenAI gym robot environment and a pick&place task.

## [Training](/Training/README.md)

We use PPO to train the robot.

## [Sim2Real](/Sim2Real/README.md)

We use the policy trained in MuJoCo to control the robot in Gazebo.