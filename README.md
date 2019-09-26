# cloudr
Instructions for running R in a docker container with an AWS cloud EC2 instance.

Basic steps are as follows:
1. Create AWS account
2. Start AWS EC2 instance
3. SSH into EC2 instance
4. Download Docker inside the EC2 instance
5. Download Rstudio inside Docker container
6. Open browser window and use Rstudio as you would downloaded onto your machine
:tada:

Why?

Setting up an EC2 instance means that the computer that you use for your project is scalable and you can access it from a browser window, which means you can work with very large data sets and scale up when neccesary without using the space on your local computer. Using docker means the project is reproducible and shareable, since you're not relying on what's downloaded to each computer you use. If you're a student, AWS will give you cloud credits that you can use to run larger instances, and when you don't need that compute power you can scale down to a free instance, while holding on to the data that's been generated. Using this method, you can run Rstudio on a chromebook or from a shared computer in the public library. 
