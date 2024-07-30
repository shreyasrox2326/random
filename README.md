# Random codes

These are a few codes that I wrote 2022 and 2023 that do some interesting things. They are not very complex and work on very basic python modules. 

## 3p-orbital.py

Plots the probability density function for a 3p orbital (with 
𝑛=3 and 𝑙=1) as a 2D heatmap using matplotlib. The orbital's axis lies in the plane. The 3p orbital was chosen because the Schrödinger equation for it is relatively straightforward to implement in Python and it exhibits an interesting shape, featuring one angular node and one radial node.

The user must enter an integer between 1 and 5 to determine the plot's resolution. Each increase by 1 doubles the resolution. Levels 1 and 2 generate plots almost instantly, while levels 3 and 4 may take a bit longer. Level 5 is not recommended due to excessive plotting time.

## valueofefinal.py


Accepts an integer input from the user to generate the value of 
𝑒 (2.718...) with the specified number of decimal places. The code uses the series expansion involving the sum of the reciprocals of factorials of natural numbers. During execution, it prints the number of terms in the series and the number of decimal places that have been evaluated. To ensure precision, the code calculates an additional 100 decimal places, which might be a bit overkill.

## sierp.py

This program plots the Sierpiński triangle, a well-known fractal, using matplotlib. The fractal is generated using the [chaos game method](https://en.wikipedia.org/wiki/Sierpi%C5%84ski_triangle#Chaos_game). The number of points that are plotted (affects resolution) may be modified.

## sierp-anim.py

This program is similar to sierp.py, but instead of showing a single final plot, it creates an animation with progressively increasing numbers of points. The user can choose to generate an animation with fewer, larger points or more, smaller points.
