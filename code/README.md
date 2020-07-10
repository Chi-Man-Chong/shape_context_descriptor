# Shape Context Descriptor: A New Approach to Assess Consistency of Two Correlated Land Boundaries

Vincent Chong  
chi-man.chong@connect.polyu.hk  
July 6, 2020  
A computer vision algorithm used in my dissertation, which was submitted to the Hong Kong Polytechnic University in partial fulfillment of the requirement for the degree of Bachelor of Science (Honours) in the Program of Geomatics  
Instructed by Dr. Yan Wai-yeung  

## Folders
* **numpy-master**: NumPy is the fundamental package needed for scientific computing with Python.  
I recommend you download the package here: https://github.com/numpy/numpy
* **pyshp-master**: The Python Shapefile Library (PyShp) reads and writes ESRI Shapefiles in pure Python.  
The main scripts are put in this folder, named as "main" & "shape"
The library was downloaded here: https://github.com/GeospatialPython/pyshp

## Steps
1. Put all the relevant files of the 1st shape in the location: "shapefiles/shape_a”
2. Put all the relevant files of the 2nd shape in the location: "shapefiles/shape_b”
3. Open main.py
4. Modify line 110 (the 1st shape) and line 167 (the 2nd shape) to be the name of your file
5. Press F5 to run the script
6. The output file is “new_xy.data” storing the x and y coordinate of the shape after performing 2D affine transformation

## Notes
1. The two shapes must be separately stored in .shp file
2. The distance between each adjacent sample vertices can be changed at line 125 (the 1st shape) and line 181 (the 2nd shape). The default is set as 1.
3. The name of output file (storing the x & y coordinates of the shape after coordinate transformation) can be modified at Line 332.
4. Changing location path is not recommended.
