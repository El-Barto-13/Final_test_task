## Task 1
pwd   
ls   
mkdir animalFarm  
cd ~/animalFarm  
cat > home_pets  
nano home_pets  
cat > pack_pets  
nano pack_pets  
ls  
cat home_pets pack_pets > animals  
cat animals  
nano animals  
cat animals  
mv animals mans_friends  
ls -al  
ls -ali  

## Task 2
cd ..   
mkdir animalFarm_system    
cd ~/animalFarm    
ls  
mv mans_friends ~/animalFarm_system 
ls     
cd ~/animalFarm  
ls  
ls -ali    

## Task 3
sudo wget https://dev.mysql.com/get/mysql-apt-config_0.8.23-1_all.deb    
sudo dpkg -i mysql-apt-config_0.8.23-1_all.deb    
sudo apt-get update    
sudo apt-get install mysql-server    

## Task 4
sudo wget https://download.docker.com/linux/ubuntu/dists/jammy/pool/stable/amd64/docker-ce-cli_20.10.13~3-0~ubuntu-jammy_amd64.deb    
sudo dpkg -i docker-ce-cli_20.10.13~3-0~ubuntu-jammy_amd64.deb    
sudo dpkg -r docker-ce-cli  