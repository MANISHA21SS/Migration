# Migration

# Name : Manisha selvakumari.S.S.
# Register Number : 212223220055

# Aim:

To move the files between virtual machine.

You can move files between virtual machines in several ways:

• You can copy files using network utilities as you would between physical computers on your network.

To do this between two virtual machine: 

• Both virtual machines must be configured to allow access to your network.

• Any of the networking methods (host-only, bridged and NAT) are appropriate.

• With host-only networking, you copy files from the virtual machines to the host and vice-versa, since host-only networking only allows the virtual machines see your host computer.

• With bridged networking or NAT enabled, you can copy files across your network between the virtual machines. 

• You can create a shared drive, either a virtual disk or a raw partition, and mount the drive in each of the virtual machines.

# Procedure:

How to Enable File sharing in VirtualBox.

Step 1. Install Guest Additions on the Guest machine.
Step 2. Configure File Sharing on VirtualBox.

Step 1. Install Guest Additions on the Guest machine.

 1.Start the Virtuabox Guest Machine (OS).
 2.From Oracle's VM VirtualBox main menu, select Devices > Install Guest Additions *
 
a. Open Windows Explorer 
b. Double click at the "CD Drive (X:) VirtualBox Guest additions" to explore its contents.

<img width="776" height="622" alt="image" src="https://github.com/user-attachments/assets/a7676776-7267-453d-a648-9b007b6910b9" />

C.Right click at "VBoxWindowsAdditions" application and from the pop-up menu, choose "Run as administrator".

<img width="1005" height="484" alt="image" src="https://github.com/user-attachments/assets/1ff7f0d4-8107-40a1-a6ee-2bfd48e57629" />

3.Press Next and then follow the on screen instructions to complete the Guest Additions installation.

<img width="792" height="523" alt="image" src="https://github.com/user-attachments/assets/9a437735-3d73-439a-9a7a-0df85e9f9eb5" />

4.When the setup is completed, choose Finish and restart the Virtuabox guest machine. Step 2. Setup File Sharing on VirtualBox Guest Machine.
5.From VirtualBox menu click Devices and choose Shared Folders -> Shared Folder Settings.

<img width="905" height="530" alt="image" src="https://github.com/user-attachments/assets/60057e84-86f2-4dc8-bc64-163d561fdbbc" />

2.Click the Add new shared folder icon.

<img width="908" height="527" alt="image" src="https://github.com/user-attachments/assets/eb668a7c-922b-4dba-9949-9f290ff52c73" />

3. Click the drop-down arrow and select Other.

   <img width="931" height="653" alt="image" src="https://github.com/user-attachments/assets/777e2198-7973-4050-9cef-4a765fb79b81" />

3. Locate and highlight (from the Host OS) the folder that you want to share between the VirtualBox Guest machine and the Host and click Select Folder. *
Note: To make your life easier, create a new folder for the file sharing, on the Host OS and give it with a recognizable name. (e.g. "Public")

<img width="880" height="448" alt="image" src="https://github.com/user-attachments/assets/50a4c471-e27e-4315-99b5-e6ef9fe2ddb4" />

4. Now, in the 'Add Share' options, type a name (if you want) at the 'Folder Name box, click the Auto Mount and the Make Permanent checkboxes and click OK twice to close the Shared Folder Settings.

   <img width="925" height="461" alt="image" src="https://github.com/user-attachments/assets/86134a16-460e-47cc-8ac9-fadd59dc902e" />

5.You 're done! To access the shared folder from the Guest OS, open Windows Explorer and under the 'Network locations' you should see a new network drive that corresponds to the shared folder on the Host OS.

# Result:
Thus the virtual machine files are moved to another VM.




