


## Install the CloudWatch Logs agent::
```linux
wget -O awslogs-agent-setup.py https://s3.amazonaws.com/aws-cloudwatch/downloads/latest/awslogs-agent-setup.py 
sudo python ./awslogs-agent-setup.py --region us-east-1


##Copy and Paste the Access key ID.> via IAM>users>securitycredential

##Copy and Paste Secret access key


##Define path for the log file to upload

```linux
/var/log/apache2/error.log
```

##View the contents of the error log in the CLI
sudo cat /var/log/apache2/error.log
