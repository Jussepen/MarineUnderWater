# Marine Species Identification Using CNNs
Product Description
Our research aims to present an efficient and effective method for the live identification and classification of aquatic fish using spatial and chromatic data.
The method to be used to identify these fish would start with the pre-processing of the video frame in our data. 
After pre-processing, images are passed to a Deep Learning model, specifically YOLO-V2, which is based on a Convolutional Neural Network. The project is used to identify fish underwater for a user's specific choice. 

# Installing Our Toolset:

Run the following command to clone the repository: https://github.com/jszdeeplearning/darkflow/tree/semeredin1

- The platform used to train model was google Colab. Run google colab by creating a google account.

- Acquire and download the CVPR 2018 dataset (200GB) : https://www.viametoolkit.org/cvpr-2018-workshop-data-challenge/challenge-data-description/

For Mac: Version 01.23.2 - https://colab.research.google.com/drive/10Z3EqynwjtyMef1ag8OhTyPBXlrAEb4y?usp=sharing
Windows: Version 01.22.3 - https://colab.research.google.com/drive/10Z3EqynwjtyMef1ag8OhTyPBXlrAEb4y?usp=sharing
Linux: Version 01.32.45 - https://colab.research.google.com/drive/10Z3EqynwjtyMef1ag8OhTyPBXlrAEb4y?usp=sharing

Source Code: https://colab.research.google.com/drive/10Z3EqynwjtyMef1ag8OhTyPBXlrAEb4y?usp=sharing

To refrence the original code: https://www.datadiscuss.com/yolo-custom-model-part1/


# How to run our software:
Currently the best working method to run our software is through the platform Google Colab.

Once the directory has been cloned,  open google colab through a google account. This can be done by opening google, opening/creating a new account, and then clicking the icon that says google colab. Another method consist of searching for google colab on the search bar. 

Frequent Errors: There are some issues with parsing the correct file type. To resolve this, be sure that your images type matches with the our type. If this is not the case implement parser function to your algorithm. 


# How to use our software:

To download software refer to documentation.
- Developers will be directed to the guide to use YOLO (You only look once algorithm).The source code is present at the bottom. 

Objective - The use of this softare is to expand the use of fish detection underwater. Developers will use this alogrithm to implement it to a 4k video in real time.

 - Clients who are people that are using the software can report bugs i.e the algorithm does not identify the correct fish. 


# How to report a bug:

To report a bug send an email to : bugReportMarineCNN@gmail.com. Please include the following to ease finding and resolving the bug. 

We would ask that any bug report contain certain information:

- Overview

- Screenshot or Report: Give as much info as possible of the situation of when the bug comes up

- Contact Information


Prototype

- Current Prototype: The current prototype only takes in images. It simulates a video with 24 fps. 

Next iteration
- implement to be able to get hd video and real time classification of fishes

 # Roles 

The roles exaplained below go beyond client spectrum and are used to describe what people working on the project should do. Take in mind that the these roles described below were selected to out of a handful of other important roles based on the impact they have on the project.
       - Developers 
       - Marine Biologist 
       - Photographers
       
       Marine Biologist: Despite its large range of applications, there are still difficulties with detecting objects. Marine Biologist will be in charge of correct classification of fish when training the model and present new data if a specific type of fish is not in the data set. They will manipulate and add to the database if needed.
       
       Photographer: There are still difficulties with detecting objects underwater due to its unique refractive properties that lead to abnormalities in lighting and color that usually are not experienced as profoundly on land. Photographers will focus on creating and processing images underwater to train the model in unique way. They will focus on helping out with  the implementation of pre-processing images before going into training.
       
       
 Disclaimer: 
 This project was developed as part of a sofware engineering course. To create the readme I used kennanmell(Git User) and Tomerach(Git User) as refrence. 
