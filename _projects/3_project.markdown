---
layout: page
title: Simulation for training agents
description: Developed a simulation environment for autonomous driving agents which has customizable training and testing parameters, customizable car parameters, simulated pedestrian and vehicular traffic and an easy to use road editor. The environment also provides a plug and play interface for supervised and reinforcement learning agents.
img: /assets/img/simulation_environment.jpg
importance: 3
category: work
---

## Demo video
<div class="aspect-ratio">
<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/yf7eyopiBVk?controls=0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<hr>

## Source code
- [Github](https://github.com/karanjoisher/vehicle_agent_simulation_environment){:target="\_blank"}

<hr>

## Features



- Vehicle with customizable parameters
- Cameras to mount on vehicle: Images captured can be used to train models as well as act as input to models while testing
- Road editor and city builder
- Traffic, pedestrian and weather simulations
- Inter-process communication: 
	- External programs (for e.g. trained python models) can control the vehicle in the simulator. 
	- The simulator sends various sensor data like position on road, nearby obstacles, camera images, etc to the external program.
	- The external program sends control commands like speed of car, steering direction, braking, etc. to the simulator.

<hr>

## Technologies used

- <strong>Languages</strong>: C#, Python
- <strong>Libraries</strong>: OpenCV, Tensorflow, Pytorch, pandas
- <strong>Tools</strong>: Unity, RenderDoc