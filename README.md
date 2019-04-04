I hosted here a project on learning by reinforcement. The technologies used are Python, Kivy, Numpy, and the Pytorch framework.

The idea of this project is to implement the deep Q-Learning algorithm in order to teach an object (let's consider here that it is a car),
to go from point A to point B. For fun, let's say he has to take a package from Rennes to deliver it to Marseille:) In practice, the
object must travel along the surface of the window from the upper left corner to the lower right corner. For the simulation, first, delete
the file last_brain.pth which is a brain for the object in a way. Once launched, the object will move randomly and then it will understand
what is expected of it and do it very well. To check the effectiveness of the learning process, you can draw lines with the left click of
your mouse to prevent it. But he will learn on his own to get to the right point by getting around the obstacle. Multiply the obstacles.
He'll always make it. This is a good start for independent driving ^^

The network consists of an input of 5 units, followed by hidden Fully connected layer of 30 neurons. The exit from the network contains 3
units corresponding to three actions of a car: drive forward, turn right and turn left.

