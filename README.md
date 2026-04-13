HAIM is a solver for the Maximum Set k-Covering Problem.

The input format

The input instance is asked to be in ascii format

See the data folder for detailed examples.

Compile

HAIM is implemented in C++ and complied by g++ with '-O3' option.

eg: g++ HAIM.cpp -O3 -o haim

Usage

HAIM is a local search and break ties randomly which needs a random seed, so the command to run HAIM is: ./haim instance_name k_value random_seed_value time_limit

For example: ./haim scp41.txt 34 44 100

scp41.txt is the name of instance and the random seed is set to 44. The algorithm will run for 100s.
