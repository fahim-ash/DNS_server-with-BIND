# Switch to root  
Firstly, switch from user to root with "su root"  
# Change ip  
Find your server and client ip with "ifconig"  
Server ip= current CentOS , Client ip = another centos installed in you vbox  
In this file, 192.168.0.104= my server ip, 192.168.0.105= my client ip, replace those  

# Change server name  
Here, my server name is ash.com and client name is desktop.com  
Change these two according to yours  
You can check your hostname with "hostnamectl"  

# Run script  
After sucessfully editing personal dns.sh run the .sh file  


# Check server  
User "systemctl status named " to check everything is ok or not  

# Client server  
Go to client server , switch to root  
Change DNS adrress, give Server ip as new DNS  
Check connection with ping




