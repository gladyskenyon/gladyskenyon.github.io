# README Agent-Based-Model Practical

## Contents
1. Introduction
3. Sheep in a field
4. Liscence

## Introduction- how to run the model and outline of software
This portfolio has been created for assignment one of the week intensive Leeds University GEOG995 Core programming course. 
The repository contains the final practical scripts and several outputs (figures and files). The code was written using Python 3 in the IUD Spyder. 

There are three key componants to the model:
* model.py- contains code to set up and control the model
* agentframework.py- defines the Agent class - object orientated
* in.txt- contains the environment which the agents will interact with    

These all need to be dowloaded in the same directory to run the model.

There are three variables to set: 
* number of agents
* number of iterations
* neighbourhood size

## Sheep in a field- what is to be expected
The model represents a field being grazed by sheep. These sheep, the agents, interact with each other and the environment. 
The model will  run through a GUI, an external window with a Menu from which you can select 'Run Model'.
There will be 20 agents which are randomly initialised in the field. The agents move randomly eating the field as they do so. The environment is a torus meaning if the sheep wonder off the field they will return on the other side.
The rescaling of the colour of the environment around the sheeps path represents where they have eaten, it will also show when the

Additionally, agents will interact by sharing their store if they come within a certain distance of one another, as defined by the neighbourhood varibale.  

## Liscence 
This project is licenced under the MIT licence. 
