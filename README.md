# Study and Implementation of a Next-Generation Firewall (NGFW) Solution using FortiGate

## Table of Contents

- [Abstract](#abstract)
- [Introduction](#introduction)
- [Methods](#methods)
  - [Installation of FortiGate Firewall in GNS3](#installation-of-fortigate-firewall-in-gns3)
  - [Configuration of Management Ports](#configuration-of-management-ports)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Abstract

The abstract of the study and implementation of a Next Generation Firewall (NGFW) solution using FortiGate would describe the process of researching and evaluating the features and capabilities of the FortiGate NGFW to determine its suitability for meeting the specific security needs of an organization. The implementation process would involve configuring and setting up the FortiGate NGFW, testing and evaluating its performance, and integrating it into the organization's existing network infrastructure. This may include implementing access control policies, creating security zones, and setting up VPN connections. The abstract would also mention the ongoing maintenance and monitoring necessary to ensure the continued effectiveness of the FortiGate NGFW in protecting the organization's network.

## Introduction

A firewall is a network security device that monitors and controls incoming and outgoing network traffic based on predefined security rules. It serves as a barrier between a trusted and untrusted network and can be positioned between a LAN and WAN network as per specific requirements to ensure the security of the network.
<div align="center">
  <img src="https://user-images.githubusercontent.com/104470002/213031170-03f5b091-ec92-4b17-b2c3-d9a481ffaa81.png" alt="Firewall Diagram" width="500">
</div>

## Methods

### Installation of FortiGate Firewall in GNS3

1. Go to the [Fortinet Support Portal](https://support.fortinet.com/asset/#/).
2. Click on support >> Download / VM Images.
4. Choose select platform KVM.
<div align="center">
  <img src="https://user-images.githubusercontent.com/104470002/213034167-2e5f4023-6693-474f-afee-02b62841990f.png" alt="KVM Image" width="500">
</div>

After you download the image, you can visit the FortiGate website to download the latest image of the firewall from the [GNS3 Marketplace](https://www.gns3.com/marketplace).
  1. Go to appliances >> Download FortiGate appliance.
<div align="center">
  <img src="https://user-images.githubusercontent.com/104470002/213035953-a8452948-6627-4b20-a4c8-dfc7fdb34a1e.png" alt="FortiGate Appliance" width="500">
</div>

Now, the installation process for FortiGate Firewall is getting started. Follow the steps below in GNS3:
a. Open the GNS3 application.
b. Go to browse all devices.
<div align="center">
  <img src="https://user-images.githubusercontent.com/104470002/213036451-698c08c2-a745-47ba-b127-0df38db9f795.png" alt="Browse Devices" width="500">
</div>
You can install new appliances on your GNS3 server by using a new template.
4. Now select Firewall devices under the Firewall devices you have to choose FortiGate qemu, then install.
5. Choose Install the appliance on the GNS3 VM (recommended) and click next and next.
<div align="center">
  <img src="https://user-images.githubusercontent.com/104470002/213036831-3d697ed5-291e-48c3-ae76-8bbb79c251e2.png" alt="Installation" width="500">
</div>
Now here you have to keep attention while selecting the images of GNS3 and FortiGate which we have downloaded:
- Choose allow custom files first.
- Select GNS3 image.
- Then select FortiGate image.
If you want to allow custom files on your computer, you will see a message like this. Click "Yes" to allow them.
<div align="center">
  <img src="https://user-images.githubusercontent.com/104470002/213037264-5ac262e3-82ca-4db3-a137-89e3a930baec.png" alt="Allow Custom Files" width="500">
</div>
6. Now you have to import the GNS3 appliance of FortiGate Firewall.
7. Then select the FortiGate Firewall image which you have downloaded from the FortiGate official website. Now FortiGate Firewall has been successfully installed in GNS3. Click next and Ok.
8. By default, FortiGate has no password, and the username will be admin. Click finish, then go to GNS3 Firewall option. Nice, it has been installed.
Note: Once FortiGate Firewall is installed on GNS3, it will ask for an evaluation license (The free trial is available for 15 days only).
<div align="center">
  <img src="https://user-images.githubusercontent.com/104470002/213037543-9b07eff4-0a74-4f9d-a5b1-9597dc1032b5.png" alt="Evaluation License" width="500">
</div>
You will also be asked to provide your registered email address and password. You can also use your FortiGate account if you want. See the topology I have designed in GNS3 for more information. To use the FortiGate Firewall’s GUI, you need to first configure its management interface. You can do this using the command line.
<div align="center">
  <img src="https://user-images.githubusercontent.com/104470002/213038202-5dadc32f-b244-4ff2-bf8f-3100375bb41c.png" alt="Management Interface" width="500">
</div>

### Configuration of Management Ports

Configuring the management ports of FortiGate is vital for ensuring seamless operational control and accessibility. Employ the command-line interface to configure IP addresses, subnet masks, and access controls for the management interface.

## Getting Started

To get started, clone this repository and follow the outlined methods for the installation and configuration of FortiGate NGFW.

## Usage

This repository serves as a guide for studying, implementing, and configuring a Next-Generation Firewall (NGFW) solution using FortiGate. Explore the documented methods and adapt them to your specific requirements.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

We extend our gratitude to the Fortinet community and the GNS3 development team for their valuable contributions and resources that have made this endeavor possible.
