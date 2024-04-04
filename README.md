# 🌞🏠
### Take-home Assignment: Solar Panel Layout Optimization 

In Singapore, available space for solar installations is limited, and a substantial portion of our solar capacity is situated on building rooftops. Optimizing rooftop space utilization is essential to achieve optimal financial returns and maximize power generation. This assignment will be about your approach to creating an optimization algorithm for the solar panel layout on a rooftop. 

This is a short assignment and our focus is on your (1) thinking process and (2) code quality. Please only spend ~3 hours of your time on this. We recommend the use of the Jupyter notebook included together in this repo, but other languages and formats are welcomed too. 


#### Objectives: 
1. Given certain set of constraints, create a layout of solar panels that maximizes the number of panels within a 2D space. 
2. Develop the algorithm in a way that is suitable for ease of further use and improvement (clean code with documentation). It should also be lightweight enough to be used in a backend service. 
3. Generate images to show the layout of solar panels. (*hint* use Python matplotlib or similar plotting libraries for visualization)
4. Write a few short explainations to describe your thinking process. This can be in the form of markdown cells in the Jupyter notebook or a separate Readme file, other formats are accepted too.
5. You will be sharing more about your approach in the next interview after this assignment. 


#### Constraints and details: 
- Solar panels sizes (length and width): 2m x 1m, 2.3m x 1m, 1.8m x 0.9m. The algorithm should work for these 3 sets of sizes.  
- Solar panels can be rotated. (*hint* for every 2D rooftop space, there is one rotation value that is optimal for that space)
- Solar panels can be arranged in portrait (length faces other panel's length) or landscape (width faces another panel's width) modes next to each other 
- Solar panels are placed in rows, where the distance between each panel within the row is 0.02m. There is a distance of 0.5m between each row. 
- Use the following points to represent different polygons of different rooftops that your layout of solar panels need to be placed within. (Units are in metres) Generate images of the result of your algorithm for each rooftop polygon:  
    - (0,0), (0, 100), (50, 0) 
    - (1.12, 130.83), (1.12, 160.83), (31.12, 160.83), (31.12, 130.83), (11.12, 100.83), (-11.12, 90.83), (-30.12, 90.83), (-20.182, 120.273) 
    - (2, 100), (2,160), (131, 160), (35, 200), (11, 300), (-20 , 90), (30, 90) 


The following pictures (from different sources, they are not related to each other) show how solar panel orientation and placement affect the maximum number of panels we can put on a rooftop. 

![Rooftop Solar Panel Placement Example 1](https://www.mdpi.com/remotesensing/remotesensing-15-01356/article_deploy/html/images/remotesensing-15-01356-g005-550.jpg )  
![Rooftop Solar Panel Placement Example 2](https://ars.els-cdn.com/content/image/1-s2.0-S0198971523000893-gr13.jpg)

