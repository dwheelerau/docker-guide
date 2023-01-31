# 202302lgonsalves  

# Introduction  
Installing and running megadetector (V5) in a docker invironment on windows.  

# Docker image source  
www.  

# Instructions  

## Instal WSL using the windows store    
1. Install Windows Subsystem for Linux (WSL) using the windows app store  
2. Type 'store' in the windows search box and select 'Microsoft store'
3. In the search bar at the top of the store search for 'WSL'

![Figure 1: Windows Subsystems for Linux app in the windows store](images/figure1.png)

- Install the app and then **reboot your computer**

## Install Ubuntu linux using WSL  
1. Once again in the windows store search for 'Ubuntu 20.04 LTS' and install the app (at the time of writing the current version is 20.04.5)  

![Figure 2: Install the Ubuntu App for WSL from the windows store.](images/figure2.png)  

2. Launch the Ubuntu app using the start menu, you will be asked for a username and password
3. Apply updates by typing the following:  
```
sudo apt update && sudo apt upgrade -y
```

![Figure 3: Apply updates](images/figure3.png)  

## Install docker desktop for windows  
1. Navigate to `www.docker.com/products/docker-desktop/` and click the Download Docker Desktop for windows button  
2. Install the application selecting `WSL` as the backend  
3. Check that everything is working by opening the `Docker Desktop` app from the start menu  
![Figrue 4: The Docker Desktop app](images/figure4.png)  



