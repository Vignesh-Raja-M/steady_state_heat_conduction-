# steady_state_heat_conduction-

2D steady state temperature distribution on thin rectangular plate.

in the program 2 examples are given the solution can be obtained in both the ways.

the element size and default boundary condition is taken as input during the run time, in the first method.

while, default boundary condition should be manually assigned in case of 2nd method.

Any way, if all the boundary conditions are provided as input, default boundary condition will not cause any error even though if it is not assigned a value a correct value.

inital value of default boundary condition is None.

lambda value of 1.5 is typical and an target error is set to 1% by default.

Lieberman technique is used and the space complexity is O(1).
the algorithm is an inplace algorithm.

outputs are solution array and % maximum error.
