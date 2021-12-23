# chef bootstrap command for ec2 instacce
 knife bootstrap 172.31.88.106 -N client.example.com --connection-user ec2-user --ssh-identity-file /home/ec2-user/chef-repo/cookbooks/ec2-web.pem --sudo
