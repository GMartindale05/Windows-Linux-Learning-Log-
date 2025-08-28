Install process for a Windows 11 machine 


Software needed: 
- Virtual Box- 
  [VirtualBox](https://www.virtualbox.org/wiki/Downloads) <br>
  *Make sure to include the Virtual Box extension Pack located at the bottom right of the link above <br>
  
- Linux- (for this instance we are using Kali Linux)<br>
Kali Linux ISO Image- [Getkali](https://www.kali.org/get-kali/)

- [7zip](https://www.7-zip.org/download.html) as the iso to be downloaded is a .7zip file (7zip is a free software)
** ALWAYS download software from trusted sources!**


Host system requirements 
Hardware Virtualization: Confirm that your systmms virtulization is enabled in the computers BIOS or UEFI settings 
Disable Hyper-V: Ensire Microsofts Hyper-V is not active on your Windows 11 host machine as if conflicts with Virtual Box 
Operaitng System: Windows 11 with the latest updates 

System Resources: 
CPU: 64 bit processor with 2 or more cores
Memory: 4GB of RAM (8GB or more is recommended)
Storage: 64GB of available disk space (20GB-80GB)
Internet Connection is required for downloading software 


Before Installing 
First Make sure your windows device is up to date and the host system requrements are met as outlined in the above section 
install Virtual Box on your device from the url listed above- make sure to download for the appropriate device you have (ex- windows host or OSX host for apple computers)

Download, Extract and install Kali Linux 
This will be to download Kali Linux iso 
Go to the url listed above to download 
Go to the Pre-built VM's and select 64 bit and then choose the virtual machine for Virtual Box (or which-ever type of software you are using)
Double Click on the downloaded iso image and choose the 7zip file manager which opens up 7zip
extract the folder contents to the file system you choose to extract the iso image to
Go to where you extracted the iso image and double click the .vbox file and this will add it to Virtual Box 
After the vm is showing in virtual box, copy the file path where the iso image was extracted to 
Click on the new VM and go to settings click on storage on the left and make sure the kali linux controller is showing and click ok, the other settings can be changed later as well 
In Virtual Box make sure the new Kali Linux VM is selcted and click start- this starts  the new installation of Kali linux

The Default user name and password is kali\kali 

