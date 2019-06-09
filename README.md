# DecimalMultiplication

The main Program file is DecMulTimeMeasure.c 

Following depnedent file are required to execute 
decContext.c decDouble.c decQuad.c -o 


GCC command to execute 
gcc DecMulTimeMeasure.c decContext.c decDouble.c decQuad.c -o Example_test_gem5


The program takes input of two operand form the text file form 
1.final_result_a.txt
2.final_result_b.txt
	
and write the executation time in output.txt and Moutput.txt

Error Message during execution in GEM-5
GEM5 SIMULATION START problem reading inputA.txt file 
Exiting @ tick 9053500 because exiting with last active thread context Simulated exit 
code not 0! Exit code is 1

I use following command
./build/X86/gem5.opt configs/example/se.py -c tests/test-progs/hello/bin/x86/linux/Example_test_gem5
