What Does CV Tree Do?

CV Tree is a program that takes a text file that describes the quantity and names of a group of bacteria contained in Fasta files located inside another folder in the project. The program enters each of these Fasta files one by one, systematically iterating through each of the genes that make up the bacteria and the amino acids that make up these genes.  It then creates a bacteria object in the program and compares each bacteria object to the others and outputs the correlation or the value for how similar each bacteria is to all the other bacteria. 

![image](https://user-images.githubusercontent.com/62827222/142179930-5335e57e-e437-43f9-a548-82ba9f2a91b4.png)



Speedup Achieved by Parallelisation


![image](https://user-images.githubusercontent.com/62827222/142180067-3e2a798f-2b87-4ed9-8e99-3717fbdc5dae.png)

I made used of the OpenMP library to expose the parallelism available within the for-loops. This made the process of mapping computations to different processors extremely simple and efficient. 

Running the Program

To run in Visual Studio 2019, it should be as simple as cloning this repository and running the solution file
