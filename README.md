
# Recon

This script is designed to provide users with the knowledge and tools necessary to conduct effective footprinting on various targets, including email addresses, domain names, IP addresses, and other relevant information. With this script, users will learn where and how to search for the information they need, enabling them to gather valuable intelligence on their targets. Whether you are a security professional, researcher, or simply curious about the online footprint of a particular entity, this script will equip you with the skills and knowledge necessary to conduct effective footprinting.



## Dependency
This script has a dependency on the Gum tool, which must be installed on the system in order for the script to run properly. Gum is a software package that provides a range of tools and utilities for network analysis and security testing, and is widely used by security professionals and researchers. Without Gum installed, the script will not be able to access the necessary functionality and may fail to execute properly. Therefore, it is important to ensure that Gum is installed and configured correctly before attempting to run this script. Once the dependency is satisfied, users can expect the script to run smoothly and provide the desired results.


## Install gum 

```bash
  sudo mkdir -p /etc/apt/keyrings
curl -fsSL https://repo.charm.sh/apt/gpg.key | sudo gpg --dearmor -o /etc/apt/keyrings/charm.gpg
echo "deb [signed-by=/etc/apt/keyrings/charm.gpg] https://repo.charm.sh/apt/ * *" | sudo tee /etc/apt/sources.list.d/charm.list
sudo apt update && sudo apt install gum
```
    

## Installation 

Install recon 

```bash
  git clone https://github.com/muhammad-shawon/recon.git
  
```
    
```bash
  cd recon
  
```

```bash
chomod +x recon   
```

```bash
bash recon  
```


## Authors

- [@muhammad-shawon](https://www.github.com/muhammad-shawon)

