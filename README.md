
(3 points) Modify one line of code in src/main/scala/project_1/main.scala so that the program generates the potential nonce from 1 to n (the number of trials) instead of randomly.
Discuss whether or not this is more efficient than the randomized approach.

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


