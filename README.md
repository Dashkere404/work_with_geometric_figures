# work_with_geometric_figures
There is a Shapes class(n_angles, angles, sides)
# It has the following attributes:
1. n_angles: the number of corners of the shape (does not change);
2. angles: a list of angle values in degrees ([90, 90, 90, 90]);
3. sides: list of side lengths ([10, 10, 10, 10]) ( between the 1st corner and the 2nd, 2nd and 3rd, 3rd and 4th, 4th and 1st);
# Implemented methods:
1. get_perimetr: return the sum of all sides of the shape
2. get_info: output information about the shape: angles, sides, perimeter
# Subclasses of the Shapes class have been created depending on the number of corners:
1. 0 - (Circle) circle
2. 3 - (Triangle) triangle
3. 4 - (Quadrangle) quadrilateral
4. n - (Nangle) n-gon
# The name attribute is added to the subclasses. The following methods are implemented for each subclass (where possible):
1. get_sq: calculates and returns the area of the shape
2. set_angles: enter new angles
set_sides: enter new side lengths
3.get_info (overdrive): output information: name, corners, sides, perimeter, area.
# Conditions for class objects:
1. Circle class objects must have a radius length, otherwise the object will not be saved;
2. Objects of the Triangle class must have a sufficient set of angles and side lengths to calculate the area of the shape, otherwise the object will not be saved.;
3. Objects of the Quadrangle class must have a sufficient set of angles and side lengths to calculate the area of the shape or have lengths for all sides, otherwise the object will not be saved;
4. Objects of the Nangle class must have either all angles or all lengths, otherwise the object will not be saved.
# Also implemented:
1 finding the diagonals and the sine between them to calculate the area for an arbitrary quadrilateral;
the function of drawing a shape when there is enough data.
