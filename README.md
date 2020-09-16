# App-for-counting-yeast-colonies

This is an app which counts the number of yeast colonies by clicking an image of a petri dish by using Fast radial Symmetry Transform.

## Abstract:
Counting yeast colonies is a task undertaken on a daily basis in research labs, after talking to some researchers at Institute of Genomics and Integrative Biology [(CSIR-IGIB)](https://www.igib.res.in/), Delhi and hearing their plight, we thought to make an app, to automate this process. 

## Procedure:
1. Data Collection : It involved getting dataset of images of different colonies
2. Preprocessing of images: It involved 2 steps:
	1. Deleting false positives, i.e outside the petri dish region. 
	2. Converting image to Grayscale
3. Algorithm: 
	1. Edge Detection
	2. Shape identification (On the basis of Convexity, Circularity, Area, Inertia Ratio) 

## Output:
![Output](https://imgur.com/3rVTZ4t.png)
![Output](https://imgur.com/nnuwbms.png)

## Technologies Used:
1. OpenCV
2. Python
3. Kivy (App development)


## Team Members:

1. [Juhi Pandey](https://github.com/runtime-terror101)
2. [Parth Garg](https://github.com/GargParth)
3. [Ria Gupta](https://github.com/ria18405)
4. [Vishesh Agarwal](https://github.com/visheshagrawal)
5. [Vrinda Singhal](mailto:vrinda18421@iiitd.ac.in)

## Presentation 

[Slides](https://docs.google.com/presentation/d/16gTr18-5aW3zMNFAO68mogXHfSwmpSphgpBPXROgwHk/edit?usp=sharing)
