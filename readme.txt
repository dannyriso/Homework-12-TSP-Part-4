These updated files find solutions to the Traveling Salesman Problem using multithreading to more efficiently find
optimal tours.

No changes were made to the compilation; the program is compiled using the Makefile code and executed with
"./tsp challenge.tsv pop_size mut_rate nthread".

The shortest tour found was 5594.68, found with num_iter = 2,000,000, pop_size = 500, mut_rate = 0.25, and
nthread = 2 (my machine only has four cores, so nthread's performance boost is limited to two threads).

The two-threaded run time is half the time taken for one-threaded, 33.485 seconds compared to 1 minute 6.572 seconds.
