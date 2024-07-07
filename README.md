# ROS noetic and foxy installation ubuntu 20.4
This repository describes the installation of ros noetic and foxy in detail.
# Software requirements:
- Virtualbox to create the virtual machine.
- Download 20.04 ubuntu mate image, Link: https://cdimages.ubuntu.com/ubuntu-mate/releases/20.04/
# Step 1: Virtual Machine Creation
- Open virtualbox and click on new to create a new virtual machine.
  
![New](https://github.com/ProShaden/Ros-noetic-and-foxy-installation/assets/174384069/a6b49ef2-ee3c-4ac3-ab63-054bd075071b)

- At the initialization of virtual machine and operating system, type a name of your virtual machine and select linux as type of operating system and ubuntu version (64 or 32 bits based on your device specification)
  
![initialization](https://github.com/ProShaden/Ros-noetic-and-foxy-installation/assets/174384069/fb3bb252-f574-4284-8129-9cf42ee74910)

- At the initialization of hardware, choose the amount of RAM and CPU also based on your device specification.

![hardware initialization](https://github.com/ProShaden/ROS-noetic-and-foxy-installation-ubuntu-20.4/assets/174384069/60105a56-6768-49e4-bad9-97eadb5d1248)

- Create a virutal hard disk by clicking on create a virtual hard disk now and the recommended disk size is 20 GB.

![hard disk creation](https://github.com/ProShaden/ROS-noetic-and-foxy-installation-ubuntu-20.4/assets/174384069/3c9f0732-83a7-483t.6-b0e6-b2573380474f)

- After the previous steps, a summary of your virtual machine will be shown, click on finish to confirm or back to edit.

  # Step 2: Ubuntu Mate Installation
  - Go to storage and click on empty then click on the little cd figure and choose a disk file (which is the 20.4 ubuntu mate image you downloaded)
  
 ![Ubuntu](https://github.com/ProShaden/ROS-noetic-and-foxy-installation-ubuntu-20.4/assets/174384069/e8d58f8b-c38b-4af5-b226-a8cd36d0b179)

  - After that, return to your virtual machine and click on start to begin with installation of ubuntu mate.
 
  - Click on install ubuntu mate and the language is English by default.
 
![ubuntu install](https://github.com/ProShaden/ROS-noetic-and-foxy-installation-ubuntu-20.4/assets/174384069/8b1517e4-83db-4e76-8a03-17c85838ca4c)

   - Select your keyboard language or let it be English.

![language](https://github.com/ProShaden/ROS-noetic-and-foxy-installation-ubuntu-20.4/assets/174384069/ba64f033-de52-4d1a-b40c-5f2c56282dc7)


 - At updates and other software, keep selection by default.
   
![default](https://github.com/ProShaden/ROS-noetic-and-foxy-installation-ubuntu-20.4/assets/174384069/63cd3f82-3080-46a3-a97d-d94c92fcf98f)

- At the installation type, click on erase disk and install ubuntu mate (this will erase your virtual disk not your actual one, so don't worry and go ahead)

![inst](https://github.com/ProShaden/ROS-noetic-and-foxy-installation-ubuntu-20.4/assets/174384069/20a6810d-9b48-456b-9bcc-f2cac4ab0fe4)

- After clicking on install now, a basic information is going to be required like your timezone, username, and password)

- Timezone:

![timezone](https://github.com/ProShaden/ROS-noetic-and-foxy-installation-ubuntu-20.4/assets/174384069/01b860e9-dc4d-4330-8ce3-8b41696b37a9)

- Username and password:

![username and pass](https://github.com/ProShaden/ROS-noetic-and-foxy-installation-ubuntu-20.4/assets/174384069/05353b48-9f15-413e-9d4e-ddaee6fa4958)

- When the installation process is done, this message will pop up, click on restart now.

![restart](https://github.com/ProShaden/ROS-noetic-and-foxy-installation-ubuntu-20.4/assets/174384069/d3a99264-ff1a-4edf-9d04-17f9fae8f7e9)

- Finally, a black screen will pop up, just press enter and then you will enter your virtual machine.

  # Step 3: ROS noetic and foxy installation
  All you have to do is to copy and paste the instrutions at the terminal and be sure to install the full desktop, you will find the instructions in the following links/
  ROS noetic: https://wiki.ros.org/noetic/Installation/Ubuntu
  ROS foxy: https://docs.ros.org/en/foxy/Installation/Ubuntu-Install-Debians.html


