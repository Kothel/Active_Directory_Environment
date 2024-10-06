<h1>Active Directory Lab
  
  
 - <a>Data Structures and Algorithms Practice (AlgoExpert)</b>
<!--
  First map out how the network is gonna be
  
-->

<!--
  Download the VMs 
-->

![image](https://github.com/user-attachments/assets/36cefb33-c294-4de2-bf13-24dec9e1e6b4)
<!--
  set up the Vm nics acording to the network map
    -172.16.0.1 is use as an adress for the internal network because it is in the B class private Ip adress range and I chose class B beause it is common
    -255.255.255.0 is the subnet mask because that is the standard subnet mask for  aclass B network
    -no Default gatway is asigned because the machine will act as the gatway to the network for itself
    -similar to the default gateway this server will act as the DNS server for the network so I will use the loopback adress
-->

![image](https://github.com/user-attachments/assets/b11ffb6d-2ab9-4b2b-8f68-6a5e26eaaede)


<!--
  add own domain 
  -- ![image](https://github.com/user-attachments/assets/2a48cc45-b551-4c97-88aa-b927cfef39c5)
  add an admin acount to domain
  -- 
  
-->
![image](https://github.com/user-attachments/assets/7175e4d3-7e82-4cf6-a2db-a921f977e1ff)

<!--
  add RAS / NAT
  - will allow clients on internal network to acess internet through the DC
-->

![image](https://github.com/user-attachments/assets/25a5582b-3aae-4e18-a810-51c999ba92a9)

<!--
  add DHCP
  - set range of DHCP to 172.16.0.100-200
  
-->

![image](https://github.com/user-attachments/assets/cdade551-344f-4b41-a961-8780b162e35f)

![image](https://github.com/user-attachments/assets/a99fb347-ed46-4cf4-b131-de24eb8802e9)

![image](https://github.com/user-attachments/assets/9c78b28a-f485-4818-8004-c6983c7f8f1e)

<!--
  use a script to add users to domain
  
-->
![image](https://github.com/user-attachments/assets/8030bc12-32f3-4678-aa36-8a664cc9316a)
![image](https://github.com/user-attachments/assets/66533f4e-380e-41d4-9b6a-5945fa56a767)


<!--
  connect client to the server in an internal network
  
-->

![image](https://github.com/user-attachments/assets/1062d56b-e67c-4c3c-90db-45cc23896615)


<!--
  Client Lease shows up in DHCP
  
-->
![image](https://github.com/user-attachments/assets/cd849ca1-60f5-4d2d-82be-aca7f98c487e)

<!--
  users created with script work
  
-->

<!--
  add RAS / NAT
  
-->
# Active_Directory_Environment
