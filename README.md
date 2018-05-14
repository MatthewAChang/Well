# Well

Well is a program I created for CPSC 213: Introduction to Computer Systems at UBC. This program uses multithreading to simulate a well in which people access for water. The well has two rules: only three people access to a well at a time and that everyone accessing the well must be of the same group, either little or big. This is done by using a mutex and conditionals. The program uses a mutex to ensure only one thread is active at a time and conditionals to signal if the person is little or big so that only group is accessing the well at any time. Each thread is a person and the program ends when each thread has accessed the well.


