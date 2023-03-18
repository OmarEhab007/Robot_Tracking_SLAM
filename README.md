# Landmark Detection & Robot Tracking (SLAM)
## Project Overview
In this project, you'll implement SLAM (Simultaneous Localization and Mapping) for a 2 dimensional world! You’ll combine what you know about robot sensor measurements and movement to create a map of an environment from only sensor and motion data gathered by a robot, over time. SLAM gives you a way to track the location of a robot in the world in real-time and identify the locations of landmarks such as buildings, trees, rocks, and other world features. This is an active area of research in the fields of robotics and autonomous systems.

Below is an example of a 2D robot world with landmarks (purple x's) and the robot (a red 'o') located and found using only sensor and motion data collected by that robot. This is just one example for a 50x50 grid world; in your work you will likely generate a variety of these maps.



The project will be broken up into three Python notebooks; the first two are for exploration of provided code, and a review of SLAM architectures, only Notebook 3 and the robot_class.py file will be graded:

***Notebook 1 :*** Robot Moving and Sensing

***Notebook 2 :*** Omega and Xi, Constraints

***Notebook 3 :*** Landmark Detection and Tracking

## Project Instructions
All of the starting code and resources you'll need to compete this project are in this Github repository. Before you can get started coding, you'll have to make sure that you have all the libraries and dependencies required to support this project. If you have already created a cv-nd environment for exercise code, then you can use that environment! If not, instructions for creation and activation are below.

- Local Environment Instructions
- Clone the repository, and navigate to the downloaded folder.
```git clone https://github.com/udacity/P3_Implement_SLAM.git```
```cd P3_Implement_SLAM```
- Create (and activate) a new environment, named cv-nd with Python 3.6. If prompted to proceed with the install (Proceed [y]/n) type y.

- Linux or Mac:
```conda create -n cv-nd python=3.6```
```source activate cv-nd```
- Windows:
```conda create --name cv-nd python=3.6```
```activate cv-nd```
At this point your command line should look something like: (cv-nd) <User>:P3_Implement_SLAM <user>$. The (cv-nd) indicates that your environment has been activated, and you can proceed with further package installations.

- Install a few required pip packages, which are specified in the requirements text file (including OpenCV).

```pip install -r requirements.txt```
- Notebooks
- Navigate back to the repo. (Also, your source environment should still be activated at this point.)
```cd```
```cd P3_Implement_SLAM```
-  Open the directory of notebooks, using the below command. You'll see all of the project files appear in your local environment; open the first notebook and follow the instructions.
```jupyter notebook```
- Once you open any of the project notebooks, make sure you are in the correct cv-nd environment by clicking Kernel > Change Kernel > cv-nd.
NOTE: While some code has already been implemented to get you started, you will need to implement additional functionality and answer all of the questions included in the notebook. Unless requested, it's suggested that you do not modify code that has already been included.
