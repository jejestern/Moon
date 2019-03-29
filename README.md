# Moon
We catalogize the craters on the Moon and find their with and depth.
To do so, we created several python scripts and worked with Jupyter. First of all ones has to know that astro_function.ipynb 
contains the functions needed in the scripts pixel_converter.ipynb and astro_workplace.ipynb. 
First of all we go through astro_workplace.ipynb to do so, we create a folder called 'Moon_pictures' in which we save all images
we want to progress. After astro_workplace.ipynb we have four text files: 'Diameters_in_pix', 'Shadow_in_pix', 'Coordinates_unsere' 
and 'Coordinates_pix'. To go on with our work we need the first three files. 
Secondly we go through pixel_converter.ipynb. This script provides us with the conversion factor to transform the pixels into meters. 
As a last step we want to calculate the real diameters and depths and create some plots. For this we use the scripts 
Diameter_Depth_12mm.ipynb and Diameter_Depth_20mm.ipynb as they name already tells, you use either one of them depending on the 
magnification your images have. This scripts uses the functions from the script Diameter_Depth_functions.ipynb.

At the end we find the diameters and the depths of all craters and their position on the Moon.
