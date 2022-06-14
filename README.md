# simple_face_swap
This is a simple faceswap algorithm to find a list of tokens.

It follows this logic:

>Loop through x coordinate for each frame:\
       if no face found (ie no x coordinate):\
                go to previous frame and find x coordinate\
                         if xcoord > 150 then this is likely a face swap\

There are two files:

1. face_swap.ipynb - contains algorithm and sample dataset

2. check_data.ipynb - a workflow to see all images by token
