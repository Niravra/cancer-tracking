# Cancer Cell Tracking Using Nanobots

## Problem Statement

	- Chemotherapy helps in tackling cancer, but it also has an impact on healthy cells
	- One of the most researched area is to design tiny robots to carry drugs directly to the cancer cells

**People Suffering from Cancer**

![Picture](https://github.com/Niravra/cancer-tracking/blob/master/Assets/Cancer%20Chart.png)


## Particle Swarm Optimization Algorithm

	- Initialize Particle having a location and velocity
	- Calculate fitness value of each particle
	- Update the global best
	- Direct the other particles to the direction of the global particle 
	- v[] = v[] + c1 * rand() * (pbest[] - present[]) + 
	c2 * rand() * (gbest[] - present[]) (a)present[] = persent[] + v[] (b)

## Cancer Cell Detection Techniques Used

	- The amount of proteins generated by the cancer cell is much more than the normal cells
	- The adhesion factor of the cancer cells is much less than the normal cells 

**The above factors represent an abnormal behavior for the cells**

## Approach for solving the problem

	- Each Nanobots will be fitted with a measuring device for calculating the amount of protien and adhsesion factor of a cell in their respective location
	- The chance factor of the cells being cancerous will be generated
	- The postion of the nanobot measuring the highest abnormality 
	value will be considered as the global best

## Features

	- Tracking of the nanobots position and the fitness factor in the particular location
	- After the nanobots come together around the global 
	best location, they can be stopped to deliver the required 
	medicine to that particular location without effecting the healthy cells


### Initial Position of the Nanobots starting at different location

![picture](https://github.com/Niravra/cancer-tracking/blob/master/Assets/InitialNanobotPos.png)

### The Position of the Nanobots after finding the most cancerous location

!![Picture](https://github.com/Niravra/cancer-tracking/blob/master/Assets/FinalNanobotPos.png)
 

