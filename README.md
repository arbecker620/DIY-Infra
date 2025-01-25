# DIY Homelab

## Introduction
This is documentation on how I created my homelab. My homelab has been focused on creating learning opportunities to host projects, create pipelines, and improve my technical acumen. There is definitely a better or optimized way of doing a homelab. I just did what I knew at the time and what challenges I weas working with. There are definitely opportunities to improve different pieces of the lab but I am trying to go low budget as possible to aviod the ire of my spouse. 

### Compoents
For this homelab I have left over Raspberry Pi I had sitting around from other projects. For this I have install Ubunutu and Docker. Since there is only two Rapberry Pis in the lab I have not created any type of ansible or images I can just preload onto a SD card for using. I have a few spare 3/4 Raspberry PI's sitting around in which I may go down further in creating these images. I have also thought about hav9ing a SFF Machien to host ProxMox on to use either a K8s cliuster or other Vms. 

Since I was looking to expand my knowledge behind a Devops platform, I designated the Raspberry PI 4 as primarily a build server. This Pi would host my Container Registry, run Automated Testing, etc...  This Pi in only hosting small projects at the moment and I am exploring increasing hard drive space. This Pi 4 is currently running Ubuuntu and Docker to help minimize the storage challenges I have with having no HDD attached. 


### Future Outlook
 - Run Model Testing/Training on Build Server
 - Add Security Scanning for Containers
 - Add K8 Machine
 - Run Terraform from Containers on Build Machine to Cloud Providers







