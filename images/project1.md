# Gabriel's Documentation of Project 1

## STEP 1 - Installing Apache and Updating the Firewall


1. Update a list of packages in the package manager

-  `sudo apt update`
2. I installed Apache2 using *apt*

-  `sudo apt install apache2`
3. I checked Apache status to see if it is running
    
- `sudo systemctl status apache2`

![Apache.Status](./images/Apache_Status.PNG)

4. I then tested how the Apache HTTP Server responds to request from the internet and the out is what I have below 
- [Apache HTTP response](http://34.205.23.237:80)

