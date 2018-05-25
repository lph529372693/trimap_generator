# trimap_generator
Generate a trimap from an input of mask image

The trimap is generated by extending a binary image from a segmented tumor. The binary image consists of 2 parts: foreground (white) which is the tumor and background (black)

Input: a binary image (from a segmented lesion)
Output: a trimap with unknown region (gray) from tumor dilation

May 25, 2018:
Update(s): create a function that converts a binary image to a trimap
To Do: documentation to accompany the code, a program that directly & recursively converts binary images to trimaps 
