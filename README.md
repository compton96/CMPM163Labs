# CMPM163Labs
 
 Lab2 Moving Cubes: https://drive.google.com/file/d/1cFFc1nCYtB62KVvQSR07Y7ArKJZs33ck/view?usp=sharing

 3D model image:

![](images/3DModels.jpg)


Lab3:
    Video: https://drive.google.com/file/d/1MkO1iNGnAZ8WpRFxMO5qwY2RV9m9s7Yc/view?usp=sharing
    For the first cube on the left, I use my own fragment shader without defining colors to get the rainbow color. 
    For the second cube on the left, I followed the tutorial to get the green specular highlight. 
    For the third cube from the left, I use the my own shader to interpolate between lavender and aquamarine. 
    For the fourth cube from the left, I made its color yellow and its specularity red, but I also made it so shiny that you can't really see the red.

Lab4:
    Questions:
        a. u = x / width + 0.5 / width;
        b. v = y / height + 0.5 / height;
        c. White

    Link:
        https://drive.google.com/file/d/1FnyRm3RNrbjeQ4QgDNhu7lDILrNc0Wfc/view?usp=sharing

    Cubes:
        For the first 4 cubes, I followed the tutorial.
        For the tiled cube, I made another add cube function. Then in the fragment shader I made checks
        to see if the texture is going past 1, and if it is, subtracting the coords by 1 to get the right location to tile from.