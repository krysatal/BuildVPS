1.First, you need a server. For example, I am using vulter at https://my.vultr.com/

2.Then select the server you want to buy, I recommend selecting a server in Japan or Los Angeles.

3.After the payment is successful, you will get the server's ip address and password.

4.Next, if you are a mac user,You can use the following command line: <br/>
  ssh root@ipAddress <br/>
  password:******** <br/>
  wget --no-check-certificate https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocks.sh <br/>
  chmod +x shadowsocks.sh <br/>
  ./shadowsocks.sh 2>&1 | tee shadowsocks.log <br/>
 
 5.At this point, you will get the ip address, port, password, and encryption method.
 
 6.Find a tool on github, then download and install, enter the information obtained in the previous step.
