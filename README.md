## AWS-basic-command
this repo made for learn command fast

# For Connection:
```linux
# ssh username@IPAdress
```
# First part to make sure most-up-to-date packeges second part get install
```linux
sudo apt-get update && sudo apt-get uprage -y
```
# Install spesific app
```linux
sudo apt-get install apache2 -y
```
# Unzip command
```linux
sudo apt-get install unzip -y
```
# Download AWS CLI tool
```linux
curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
```
# Unzip Files
```linux
unzip awscliv2.zip
```
# Install 
```linux
sudo ./aws/install
```
# Verify Versions
```linux
aws --version
```
# To give permission edit the HMTL File
```linux
sudo chmod 777 /var/www/html/index.html
```
# Check that Apache installed correctly:
```linux
systemctl status apache2
```

# Verify the process is running:
```linux
ps aux | grep apache
```


