# Algorithm for measuring fluorescence intensity on GUVs
Accepts _.lif_ files (obtained from Leica microscopes)

In the first cell, start by changing the variable that points to the address where the GUV file is located in your computer:
> fpath = 'your path'

then change the name of your file here:
>fname ='your file name'

In the second cell, choose the GUV of interest **img = new.get_image(0)**  by changing the number between brackets.  
Important: The first GUV stored in a _.lif_ file is in position 0.

#### Run this cell and follow the instructions, tha means, trace the desired number of lines across the membranes and press **Q** when your are done. 

#### The mean fluorescence intensity is shown below this cell. You can also verify the intensity line profile of each line in the graphs.
