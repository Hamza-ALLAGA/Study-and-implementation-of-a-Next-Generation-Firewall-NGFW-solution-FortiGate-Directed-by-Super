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
![image](https://user-images.githubusercontent.com/104470002/213031170-03f5b091-ec92-4b17-b2c3-d9a481ffaa81.png)

## Methods

### Installation of FortiGate Firewall in GNS3

1. Go to the [Fortinet Support Portal](https://support.fortinet.com/asset/#/).
2. Navigate to the "Download / VM Images" section.
3. Choose the appropriate KVM image for your platform.
![image](https://user-images.githubusercontent.com/104470002/213034167-2e5f4023-6693-474f-afee-02b62841990f.png)
4. Visit the [GNS3 Marketplace](https://www.gns3.com/marketplace) to acquire the latest FortiGate appliance image.
5. Download the FortiGate appliance image from "Appliances."
![image](https://user-images.githubusercontent.com/104470002/213035953-a8452948-6627-4b20-a4c8-dfc7fdb34a1e.png)
6. Follow the installation process in GNS3:
   - Open the GNS3 application.
   - Browse all devices and select FortiGate qemu for installation.
   - Choose "Install the appliance on the GNS3 VM" and proceed.
![image](https://user-images.githubusercontent.com/104470002/213036831-3d697ed5-291e-48c3-ae76-8bbb79c251e2.png)
7. Pay attention when selecting GNS3 and FortiGate images:
   - Allow custom files and select GNS3 image, then FortiGate image.
![image](https://user-images.githubusercontent.com/104470002/213037264-5ac262e3-82ca-4db3-a137-89e3a930baec.png)
8. Import the FortiGate appliance into GNS3 and proceed with installation.
9. The default credentials for FortiGate are admin/admin. Finish the installation and enter the GNS3 Firewall option.
   **Note:** FortiGate will request an evaluation license, available for 15 days.
![image](https://user-images.githubusercontent.com/104470002/213037543-9b07eff4-0a74-4f9d-a5b1-9597dc1032b5.png)
10. Provide your registered email address and password. Your FortiGate account can also be used. Explore the designed topology in GNS3 and configure the management interface for accessing FortiGate's GUI.
![image](https://user-images.githubusercontent.com/104470002/213038202-5dadc32f-b244-4ff2-bf8f-3100375bb41c.png)

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
