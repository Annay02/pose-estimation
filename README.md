# Pose estimation

# Introduction 
This work focuses on an automated system for assessing fall risk in the elderly using the Timed Up-and-Go (TUG) test. It utilizes a standard camera and 2D pose estimation to track key body points, providing an objective, cost-effective alternative for clinical mobility evaluation.

# Demo 
Below is a demo of the pose estimation using tensorflow

https://github.com/user-attachments/assets/44d4eda9-b596-4bf6-a427-a90add855622




# Installation


# Getting Started

( README index.html
To test the video tracker:
1. In VSC install extension "Live Server"
2. In VSC, navigate to the folder where index.html is located (the local location you chose on your computer for the repot, see the Github guide)
3. Right-click index.html and select 'Open with Live Server' ) ? 


# Graphs 
Below is information on graph generation: 
* The file "CodeTug.m" loads data from two files, calculates the mean values for each file, plots the means, and shows the differences at various time points. It provides a visual comparison of the differences between automatic and manual timing for a "Time Up and Go" test.

Graph 1 
![Alt text](https://github.com/Annay02/pose-estimation/blob/main/Graphs/Avrage%20for%20Manual%20and%20Automatic%20Time%20Up%20and%20Go.png)
* The graph titled "Average for Manual and Automatic Time Up and Go"displays the mean values of the times recorded manually and automatically. This graph highlights the average performance time recorded by each method, allowing for a straightforward comparison of their results across different test runs. 

Graph 2 
![Alt text](https://github.com/Annay02/pose-estimation/blob/main/Graphs/Standard%20Deviation%20.png)
* The graph titled "Difference and Standard Deviation between Automatic and Manual Time Up and Go" shows time differences between automatic and manual Time Up and Go (TUG) measurements for steps 1–6. Each point represents the average difference per step, with error bars showing standard deviation. Positive values mean the automatic method took longer; negative values mean it was faster.

Graph 3 

![Alt text](https://github.com/Annay02/pose-estimation/blob/main/Graphs/TUG.jpeg)
* This graph illustrates a potential execution of a TUG (Timed Up and Go) test. Once the test is completed, a file is generated. This file can be imported into software such as MATLAB, where a graph can be produced showing the measured time for each movement.



