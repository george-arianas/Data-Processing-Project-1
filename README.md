
# Large Scale Data Processing: Project 1
Name and EagleId1: George Arianas 50277148
<br> Name and EagleId2: Nathan French 44545498

## Question 1
(4 points) Run the program on your local machine to solve cases k = 2,3,4,5,6.
For each k, provide xS, its hash value, the total time elapsed, and the number of trials.

k = 2, trials = 1,000, nonce, hash, and seconds elapsed in picture
![alt text](https://github.com/george-arianas/Data-Processing-Project-1/blob/main/k2.jpg)

k = 3, trials = 10,000, nonce, hash, and seconds elapsed in picture
![alt text](https://github.com/george-arianas/Data-Processing-Project-1/blob/main/k3.jpg)

k = 4, trials = 10,000, nonce, hash, and seconds elapsed in picture
![alt text](https://github.com/george-arianas/Data-Processing-Project-1/blob/main/k4.jpg)

k = 5, trials = 10,000,000, nonce, hash, and seconds elapsed in picture
![alt text](https://github.com/george-arianas/Data-Processing-Project-1/blob/main/k5.jpg)

k = 6, trials = 50,000,000, nonce, hash, and seconds elapsed in picture
![alt text](https://github.com/george-arianas/Data-Processing-Project-1/blob/main/k6.jpg)

## Question 2
(3 points) Run the program on GCP to solve the case k = 7. Provide xS, its hash value, the total time elapsed, and the number of trials. Describe your cluster's configuration (number of machines, number/type of cores, etc.) and your process for estimating the number of trials needed in order to find the nonce.

k = 7, trials = 100,000,000, nonce, hash, and seconds elapsed in picture
![alt text](https://github.com/george-arianas/Data-Processing-Project-1/blob/main/k7.jpg)

The cluster configuration is as follows:
![alt text](https://github.com/george-arianas/Data-Processing-Project-1/blob/main/cluster%20config.jpg)
We used 1 master node and 2 worker nodes with 2 vCPUs and 1 core each.

## Question 3
(3 points) Modify one line of code in src/main/scala/project_1/main.scala so that the program generates the potential nonce from 1 to n (the number of trials) instead of randomly.
Discuss whether or not this is more efficient than the randomized approach.

This is the original code for the random nonce, which we modified:
![alt text](https://github.com/george-arianas/Data-Processing-Project-1/blob/main/original%20nonce.jpg)

his is the modified code, generating a nonce starting from 1:
<br>![alt text](https://github.com/george-arianas/Data-Processing-Project-1/blob/main/modified%20nonce.jpg)

This is the result when we ran the program for k=6:
![alt text](https://github.com/george-arianas/Data-Processing-Project-1/blob/main/sequential%20code.jpg)

The different ways of generating the potential nonce are close in time elapsed, but the original approach of a random nonce is faster.
