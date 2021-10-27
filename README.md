# Cybertalents-Bean-Writeup
The steps for solution of the Cybertalents   Bean challenge

.
.


![bean](https://user-images.githubusercontent.com/73122852/139157796-cfaf950f-d184-448e-9206-26d681e61fde.png)


# First Step

#### 1- Check the robots.txt file



![error](https://user-images.githubusercontent.com/73122852/139158046-91513644-6847-4b5a-aeda-8a0081fa92b8.png)


**Found nginx 1.21.0**

## So we will try to guess any related files Using   =>  dirb   or   dirsearch 

![dirb](https://user-images.githubusercontent.com/73122852/139158892-339b7db5-0acb-467b-96cb-a4c1e5e90634.png)
# or
![dirsearch](https://user-images.githubusercontent.com/73122852/139158899-cecff438-cc1a-45d3-a248-3e7ce66ff9b8.png)


## Then I Found a related file 
![files](https://user-images.githubusercontent.com/73122852/139159003-28ff38fe-5190-4b41-b32d-5efbf2481be6.png)


## When I Write the path  I Found Internal Files

![ALL files](https://user-images.githubusercontent.com/73122852/139159308-cdac3b74-1a21-45eb-9fd1-6315014a6aeb.png)



## I Found Passwd & Shadow files That exist in etc directory

![file](https://user-images.githubusercontent.com/73122852/139159426-3fd31e6f-52e5-4711-92a8-c8bc6c117a95.png)


## that is Directory traversal vulnerability in nginx

# you should go home as he told you in the challenge 

![flag](https://user-images.githubusercontent.com/73122852/139159938-bbe53808-00e6-49fe-8d16-ec8ff5bfce40.png)


# Finaly we Found the Flag

![the flag](https://user-images.githubusercontent.com/73122852/139159973-d4a8017e-5581-4de8-9f18-6cedc6451811.png)





