# SAT-solver
The SAT solver checks if the given CNF formula evaluates to true for some arbitrary input combinations.

SAT SOLVER by VIGNESH RAGHAVAN, ASHISH GONDIMALLA

COMPILING:

> g++ main.cpp -o mySAT -O3

EXAMPLES:

Default is Run mySAT with HCL solver and Debug OFF mode.

> mySAT benchmarks/sat100/01.cnf



To run mySAT with CBCP/NCBCP/NHCL solver. Update mySolver enum variable in main.cpp ->

> mySolver = CBCP; //For CBCP solver.

> mySolver = NCBCP; //For NCBCP solver.

> mySolver = NHCL; //For NHCL Solver.

And, then compile and run.

> mySAT benchmarks/sat100/01.cnf



To run mySAT with LOW/MED/HIGH Debug mode. Update myDebug enum variable in main.cpp ->

> myDebug = LOW; //For Debug LOW.

> myDebug = MED; //For Debug MED.

> myDebug = HIGH; //For Debug HIGH.

And, then compile and run.

> mySAT benchmarks/sat100/01.cnf
