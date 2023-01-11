# Autonomous Driving Agent in different environmental conditions
This project was done  for the Deep Learning for Autonomous Cars module at the University of Ulm. It is a result of the collective effort by Ksenia Vinogradova and Rohan Asthana.

## Introduction
The main aim of this project was to adapt an autonomous driving agent to driving in a simulated OpenAI environment that it was not trained on. The agent was initially trained in default ‘good weather daytime’ conditions using a CNN network. The environment was then modified to introduce ‘bad weather’, such as rain and snow, as well as night, by adding respective animations and manipulating colours of the grass and the road. To allow an autonomous agent to still drive in this environment, a Pix2Pix network was used to convert the images from the environment into ‘good weather daytime’ images before giving them to the agent as input. This successfully improved the performance of the agent in the unfamiliar ‘bad weather’/night environment making it comparable to the familiar ‘good weather daytime’ environment.

5 different conditions were used in this project:
- Rain
- Snow
- Night
- Rainy Night
- Snowy Night

[!]fig1.png
