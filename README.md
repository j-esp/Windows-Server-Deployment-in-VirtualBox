![image](https://github.com/user-attachments/assets/412db7d1-2682-4627-9e97-3a4eb1fa71e0)

<h1>Windows Server Deployment in VirtualBox</h1>
In this activity, I will demonstrate the installation of Microsoft Windows Server within VirtualBox. This setup will serve as a foundation for leveraging Active Directory, a crucial component for managing user and resource access in a business environment.

<h2>Technologies and Platforms</h2>

- Oracle VM VirtualBox
- Windows Server 2016

<h2>Operating Systems</h2>

- Windows 10 (2016)

<h2>Procedure</h2>

![1](https://github.com/user-attachments/assets/a256b0ca-2dca-4cf1-b6f2-28bfeeb3bbb5)

<p>
First, I installed VirtualBox, which can be downloaded <a href="https://www.virtualbox.org/wiki/Downloads"> here</a>. I selected the version that is compatible with my host operating system, which is Windows. 
</p>

![2](https://github.com/user-attachments/assets/6b54c340-97b9-4361-813a-79a894bfd87e)

<p>
Next, I installed Windows Server 2016's ISO, which may be downloaded <a href="https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2016"> here</a>.
</p>

![image](https://github.com/user-attachments/assets/ba51a32e-a834-4d57-88aa-33540b649bfa)

<p>
I then launched VirtualBox Manager and configured a new virtual machine. For the operating system version, I selected Windows Server 2016.  
</p>

![4](https://github.com/user-attachments/assets/a76edbab-2d4a-4760-bb3b-b355d1d43c91)

<p>
Upon initializing the virtual machine, I encountered an error message which was resolved through inserting the Windows Server ISO file and proceeded with the installation.  
</p>

![5](https://github.com/user-attachments/assets/3d1657f5-c8b8-4705-a2a5-1c235f5a9d91)
![6](https://github.com/user-attachments/assets/6ec29460-265b-4aad-bca9-0bcdafebb742)

<p>
During the operating system installation, I used the ISO file I had downloaded, which was the Datacenter Evaluation edition. For my requirements, it was crucial to select the “Desktop Experience” option, as the alternative would only provide a command-line interface. 
</p>

![7](https://github.com/user-attachments/assets/97e6e1b0-6b2b-4c4f-a2be-58fb97f57285)

<p>
Since this was a fresh installation, an upgrade was not required. I chose the “Custom: Install Windows Only” option.
</p>

![8](https://github.com/user-attachments/assets/f432d074-131f-4959-b0dc-8d2af72412de)
![9](https://github.com/user-attachments/assets/4afacd9c-5695-4de0-8e7f-a00fcaff587b)

<p>
After the installation, I set up the server credentials. 
</p>

![10](https://github.com/user-attachments/assets/3cec893f-095e-45bd-a426-8c7149e06982)

<p>
Due to the local PC's keyboard inputs not functioning, I proceeded through VirtualBox's interface.  
</p>

![11](https://github.com/user-attachments/assets/137cd34b-cf73-4505-ad9b-572356329dd3)

<p>
With Server Manager successfully installed, the overall installation process was completed without issues. The server is now fully set up and ready for further configuration. 
</p>

<h2>Key Takeaways</h2>
The installation of Windows Server is an integral step in configuring Active Directory. This setup enables management of users and computers within a domain.
