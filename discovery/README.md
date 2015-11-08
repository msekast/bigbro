# Explore large 3D city model on mobile devices togehter

## Vision

Goal of this project is to allow multiple persons to explore a large city model from their mobile devices, alone and toghether. It provides easy navigation in a mobile device fashion and a multi player mode, where exploration happens together, sharing the same view in real time.

## Minimize data transferred and memory footprint on mobile device
Needed for this project is the creation of a software to display a very large 3D model on a mobile device with a minimal memory footprint and a minimal amount of 3D model data transferred over the network. On the mobile device side a fast and slim visualization technique has to be developed within an application which is capable to navigate in 3D. For transferring the model data from a cloud component to the mobile device a mechanism has to be invented, which minimizes the amount of data transferred over the network. On the cloud a component has to provide and prepare the 3D model information in a way that makes consumption possible over the network, this component will be part of the project but focus of the project is the mobile device side.

## Real time interaction between multiple viewers
Coordination of naviagtion between multiple viewers in real time has to happen. This will allow users to interactively explore the model from their own mobile device toghether, showing each other around or pointing each other to a point of interest.

Target platform
---------------
This project should target all major mobile platforms, this includes in paticular Android, iOS and Web. It is also part of this project to find the best way to acheive this, from a technical but from a practical point of view as well. Ideally the application developed should be as easy as possible portable to other mobile platforms. Hovewer there will be no compromise in performance and usability in favor of portability. 

Scope
-----
The scope of this project is a working prototype. The prototype will display an appropriately prepared large 3D model. The 3D model has to be explorable by navigating and by looking around. Example data used in this prototype will not be shared or published. The prototype should provide a touch and user friendly navigation functionality. The focus of the work will be to provide a fully working 3D viewer, highly interactive and fast. The viewer software should be developed in a componentized  manner, so that this mobile viewer component can be customized and reused. The project software provided will have a MIT license.

Disclaimer on cloud service parts
---------------------------------
This project will focus on the client side software and define a set of interfaces that it requires to communicate with a cloud component. The interacting cloud service parts and data will not be published and solely used for development and presentation purposes. This component will not be part of the prototype and might be hard wired to a given set of models or entirely mocked.

Deliverables
------------
The software and documentation will be provided in this GIT repository. It should have clear explanation and advise how the data required by the software has to be prepared and how the interfaces look like.
