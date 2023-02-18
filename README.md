# aws_ssh_sock_proxy

# ssh -i key_aws_california.pem  ec2-user@54.215.128.17  -N -D 9090

##setup sock proxy:

# ssh -i "REDHAT_OS.pem" ec2-user@ec2-15-206-157-96.ap-south-1.compute.amazonaws.com  -N  -D  9090

Launch chrome browser from this command

# "C:\Program Files (x86)\Google\Chrome\Application\chrome.exe" --user-data-dir="%USERPROFILE%\proxy-profile" --proxy-server="socks5://localhost:9090"


speed test using curl:

# curl -s -o /dev/null -w "%{time_total}\n" http://54.215.128.17/
