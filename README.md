# yolo-bbox-visualizer
Generally, we can draw bounding boxes using the coordinates given as X_min, Y_min , X_max, Y_max   OR   X, Y ,W, H, but when these coordinates are  normalizes to the scale of 0-1 ( for ex, images annotated by labelimg have the output coordinates of bboxes in this scale ), it can be a little tricky to draw bbox. So i have a little script to change the scale and  to draw bbox on objects if the coordinates are on the scale 0-1 .

To use this code just change the paths given in main.py file, provide input images, labels.
