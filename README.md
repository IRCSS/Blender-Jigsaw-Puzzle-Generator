# Blender-Jigsaw-Puzzle-Generator
python and geometry nodes for converting any 2D image to a jigsaw puzzle. Useful for animation, games or 3D printing. This was tested on Blender Version 4.1.1.

![screenshot](documentation/puzzleMaker.gif)

To use you need to run the script, which will look for an image "example.jpg" placed next to the blend file, load it and make a puzzle out of it. 
Per default it make a 400 piece puzzle, if you want a different piece count, you can change it at the end of the script (line 289) as a input paramter to the function. 

For technical explaination of how the code works, read my blog post: https://medium.com/@shahriyarshahrabi/creating-a-jigsaw-puzzle-in-blender-using-geometry-nodes-and-python-509c88d6af24
