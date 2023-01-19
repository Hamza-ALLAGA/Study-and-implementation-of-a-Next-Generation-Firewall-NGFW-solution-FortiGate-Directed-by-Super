# Study-and-implementation-of-a-Next-Generation-Firewall(NGFW) solution-FortiGate


# Abstract 


The abstract of the study and implementation of a Next Generation Firewall (NGFW) solution using FortiGate would describe the process of researching and evaluating the features and capabilities of the FortiGate NGFW to determine its suitability for meeting the specific security needs of an organization. The implementation process would involve configuring and setting up the FortiGate NGFW, testing and evaluating its performance, and integrating it into the organization's existing network infrastructure. This may include implementing access control policies, creating security zones, and setting up VPN connections. The abstract would also mention the ongoing maintenance and monitoring necessary to ensure the continued effectiveness of the FortiGate NGFW in protecting the organization's network.
# Introduction 

A firewall is a network security device that monitors and controls incoming and outgoing network traffic based on predefined security rules. It serves as a barrier between a trusted and untrusted network and can be positioned between a LAN and WAN network as per specific requirements to ensure the security of the network.
![image](https://user-images.githubusercontent.com/104470002/213031170-03f5b091-ec92-4b17-b2c3-d9a481ffaa81.png)

# Methods


## Install Fortigate Firewall in Gns3
1. Go to site https://support.fortinet.com/asset/#/.
2. Clicks on support >> Download /VM Images 
4. Choose select platform KVM
[image](https://user-images.githubusercontent.com/104470002/213034167-2e5f4023-6693-474f-afee-02b62841990f.png)

After you download the image, you can visit the Fortigate web-site to download the last image of the firewall https://www.gns3.com/
marketplace
      1. Go to appliances >> Download Fortigate appliance
[image](https://user-images.githubusercontent.com/104470002/213035953-a8452948-6627-4b20-a4c8-dfc7fdb34a1e.png)

Now, the installation process for Fortigate Firewall is getting started.
So, please follow the steps below in GNS3.

a.  Open the Gns3 application

b. Go to browse all devices as per the below snapshots.

[image](https://user-images.githubusercontent.com/104470002/213036451-698c08c2-a745-47ba-b127-0df38db9f795.png)


 You can install new appliances on your GNS3 server by using a new template.
4. Now select Firewall devices under the Firewall devices you have to choose Fortigate qemu, then install
5. Choose Install the appliance on the Gns3 Vm (recommended) and the click next and next
                                [image](https://user-images.githubusercontent.com/104470002/213036831-3d697ed5-291e-48c3-ae76-8bbb79c251e2.png)


Now here you have to keep attention while selecting the images of gns3
and Fortigate which we have downloaded.
  >>  Choose allow custom files first.>>
     Select Gns3 image.>>
    Then select Fortigate image
   
   
   If you want to allow custom files on your computer, you will see a
message like this. Click "Yes" to allow them.
[image](https://user-images.githubusercontent.com/104470002/213037264-5ac262e3-82ca-4db3-a137-89e3a930baec.png)

6. Now you have to import gns3 appliance of Fortigate Firewall.
7. Then select Fortigate Firewall image which you have downloaded from
the Fortigate official website. Now Fortigate Firewall has been successfully
install in Gns3 then click next and Ok.
8. By default Fortigate has no password and username will be admin then
click finish, then go to Gns3 Firewall option. Nice it has been installed.
Note :
Once Fortigate Firewall is installed on GNS3, it will ask for an evaluation
license. (The free trial is available for 15 days only.)
[image](https://user-images.githubusercontent.com/104470002/213037543-9b07eff4-0a74-4f9d-a5b1-9597dc1032b5.png)

8. By default Fortigate has no password and username will be admin then
click finish, then go to Gns3 Firewall option. Nice it has been installed.
#### Note :
Once Fortigate Firewall is installed on GNS3, it will ask for an evaluation
license. (The free trial is available for 15 days only.)


You will also be asked to provide your registered email address and
password. You can also use your Fortigate account if you want. See the
topology I have designed in GNS3 for more information.
To use the Fortigate Firewall’s GUI, you need to first configure its ma-
nagement interface. You can do this using the command line.[image](https://user-images.githubusercontent.com/104470002/213038202-5dadc32f-b244-4ff2-bf8f-3100375bb41c.png)

To use the Fortigate Firewall’s GUI, you need to first configure its ma-
nagement interface. You can do this using the command line.[image](https://user-images.githubusercontent.com/104470002/213038301-c13b880c-6547-4401-b651-0810dc4ea3ee.png)



## Configure management ports of the Fortigate
