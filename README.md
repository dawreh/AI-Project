# AI-Project

COMMANDS FOR MAC-TERMINAL:
Compilation: javac *.java
Execution: java Main


PRINTING DISTANCES FOR COMPARISION:
One can also control the prints of the distances
to the terminal by imposing/removing the comment
on the statement below in the GeneticAlgorithm class:

Print_Solution_Distances(population_distances_for_all_generations);

Several other debugging functions are available in the GeneticAlgorithm class
that can be used for comparisions. Follow the comments in the class if you want
to make different checks.


CHANGING CONSTANTS:
One can also change the constants in the Constants.java file. However, the person
changing the values there should be aware of the constraints imposed on the
constants. A detailed description can be found in the Constants class in the
Constants.java file.


REMOVING MUTATION OR CHANGING MUTATION FUNCTION:
Another manipulation that can be made easily is by simply imposing/removing
a comment on the statement below in the GeneticAlgorithm class:

population = Mutation.SOME_MUTATION_FUNCTION(...);

in which case no mutations will occur. Furthermore, we also have several "public"
mutation functions that can be tried out in the Mutation class.
