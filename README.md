# AWS Realtime Interview Questions With Answers

##  1. Recover an Elastic IP address

#### If you have released your Elastic IP address, you might be able to recover it. The following rules apply:

 - You cannot recover an Elastic IP address if it has been allocated to another AWS account, or if it will result in your exceeding your Elastic IP address limit.
 - You cannot recover tags associated with an Elastic IP address.
 - You can recover an Elastic IP address using the Amazon EC2 API or a command line tool only.
 - Use AWS CLI or Powershell
 - Use the allocate-address AWS CLI command and specify the IP address using the --address parameter as follows.

   ``` 
    aws ec2 allocate-address --domain vpc --address 203.0.113.3
   ```
   

   
