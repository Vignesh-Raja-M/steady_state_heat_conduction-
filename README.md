# steady_state_heat_conduction-

2D steady-state temperature distribution on a thin rectangular plate.

modules used:
        Numpy

About: 
        The program is used to compute steady-state temperature distribution on a thin rectangular plate.
        Lieberman technique is used and the space complexity is O(1) which makes it an in-place algorithm.
        Time complexity depends on the number of meshes generated.
        
Default conditions:
        The initial value of the default boundary condition is set to None.
        Lambda value(a constant used for the iterative approach) of 1.5 is typical and maximum error is set to 1% by default.
        
inputs: *Default boundary condition (taken during run time/ mannually assigned)
        *mesh element size (taken during run time)
        *Boundary conditions (pass by value)
        *Plate dimensions (pass by value)
         maximum allowable error % (pass by value)
         lambda value (range 1-2) (pass by value)
         
         Note: *indicates mandatory inputs
         
outputs: solution NumPy array, % maximum error.

        Note: In this program, 2 examples were provided as tutorials.
              The element size and default boundary condition are taken as input during the run time in the first example.
              while the default boundary condition should be manually assigned in the case of 2nd example.
              If all the boundary conditions are provided as input, the default boundary condition will not have any effect.
