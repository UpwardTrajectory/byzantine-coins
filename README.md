# byzantine-coins
Computer Vision recognition of Byzantine "Christ" coins into their mint class [A - G]

This is for a coin collector, some images are wide (both sides of the same coin next to each other) some are square-ish (only 1 side). I'm trying to build a classifier into one of about 6 different classes, but the data set is fairly small and also imbalanced.  (30000 images, smallest class has less than 500)

My To-Do List:
1) split the "both-sides" images
2) grayscale the images
3) resize to standard dimensions
4) separate coin from background
5) rotate so they are all oriented roughly the same
6) augment the dataset using various techniques (but not flips) 
7) connect the fronts and backs into a final "both-sides" image (maintaining the original target label throughout the process)
8) train my model