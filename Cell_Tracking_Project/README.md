# Cell Tracking Project
Check the requirements.txt 
To run open jupyter file and in the main function enter the (dataset you want to see, sequence from that dataset)
Note from dataset 1, sequence 1 and 2 were used for developing the neural net hence, test with sequence 3 and 4.

The training of the neural net and then the segmentation of dataset 1 was done by me. The segmentation of dataset 2 and 3 and the tracking of cells and mitosis was done by the other members of the group. Dataset 1 was a challenge set and hence, it took the most time to segment. The results obtained for the segmentation had an accuracy fo 75%. This is detailed in the report.

Our program shows the segmentation, tracking, mitosis and analysis of cell motion for different image sequence.
We developed a program that detects cells and shows a bounding box. Cells are tracked from frame to frame and mitosis events are identified. Each cells track is shown as well as the amount of cells found in the image. 
A predicted cell mitosis is shown by changing the colour of the cell bounding box from green to white. We also see this as an output in the terminal. Information about mother and daughter cells are also shown. When a mitosis occurs, each daughter cell is a new cell with a unique id. 
Tracking can follow each cells. If you press "p" on your keyboard, you can choose a cell to analyse.
Analysis of this cell will present information in the terminal as per task 3 requirements, ie speed of cell, total distance travelled, net distance travelled, and the confinement ratio of the cells motion. 

### NOTE
Images obtained from the neural net are stored in cell_images folder in the repository. The code for training the neural net and then obtaining the images for sequences 3 and 4 can be accessed by the following [link](https://colab.research.google.com/drive/1xkDg-9pV3FnKspTvoRRbO2EA6jX8QRab?usp=sharing).


