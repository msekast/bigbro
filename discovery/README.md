Project – 3D mobile: Minimize data transferred and memory footprint on mobile device
====================================================================================
Goal of this project is the creation of a software to display a very large 3D model on a mobile device with a minimal memory footprint and a minimal amount of 3D model data transferred over the network. On the mobile device side a fast and slim visualization technique has to be developed within an application which is capable to navigate in 3D. For transferring the model data from a cloud component to the mobile device a mechanism has to be invented, which minimizes the amount of data transferred over the network. On the cloud a component has to provide and prepare the 3D model information in a way that makes consumption possible over the network, this component will be part of the project but focus of the project is the mobile device side.

Target platform
---------------
The world wide leading mobile operating system is Android, therefor the primary platform for this project will be Android as well. Ideally the application developed should be as easy as possible portable to other mobile operating systems, such as iOS.

Scope
-----
The scope of this project is a working prototype. The prototype will display an appropriately prepared large 3D model. The 3D model has to be explorable by navigating and by looking around. Example data used in this prototype will not be shared or published. The prototype should provide a touch and user friendly navigation functionality. The focus of the work will be to provide a fully working 3D viewer, highly interactive and fast. The viewer software should be developed in a componentized  manner, so that this mobile viewer component can be customized and reused. The project software provided will have a MIT license, but interacting cloud service parts and data will not be published and solely used for development and presentation purposes.

Deliverables
------------
The software and documentation will be provided in this GIT repository. It should have clear explanation and advise how the data required by the software has to be prepared and how the interfaces look like.

Approach
--------
Large 3D models can have sizes of multiple 100 MB and even more. Such large models can not be transferred entirely to mobile devices, to save bandwidth and storage space on the mobile devices. Even though modern mobile devices have powerful CPU's and GPU's, they  still do not compare to todays desktop counterparts and moreover data transferred might be expencive. For these reasons it is appropriate to not transfer large parts of 3D models to mobile devices but instead to optimize the visualization technique. While the available 3D API's on the mobile devices are powerful, they should still be used with care, because on mobile devices, apart from the limited computing power, battery power is limited and it should be saved wherever possible. Therefore it is appropriate to delegate some computing to backend servers, which can prepare the data in a way that consumption on mobile devices can be simplified. Of course this comes with a price tag, so the backend work necessary should be limited as well.

Navigation
----------
3D navigation is hard, on mobile devices it is even harder, without the pointing devices available on desktops. Therefore full free 3D navigation seems to be a thing that could be tailored for mobile devices, without losing functionality, better yet, by even improving usability on mobile devices. By adapting the navigation to mobile devices, the goal has to be to limit the functionality in a way that the user will not have the impression of limitation, but instead of a simplification and from a technical point of view to use this fact for optimization on the computing side.