# Install-VMWare-Install-Kali-Linux-and-Install-Sleuth-Kit

### Name: Richardson A
### Reg No: 212222233005
## AIM:

To install VMware, set up Kali Linux as a virtual machine, and install Sleuth Kit for digital forensic analysis.

## **Design Steps:**

### **Step 1: Install  VirtualBox**

### **Installation Steps:**
1. Download the **Windows hosts** `.exe` file from the official VirtualBox website.  
2. Run the installer and follow the on-screen instructions.  
3. Once installed, launch VirtualBox to verify the installation.


### **Step 2: Install Kali Linux on VirtualBox**
🔗 **Download Kali Linux VM**: [Click Here](https://www.kali.org/get-kali/#kali-virtual-machines)  

### **Installation Steps:**
1. Download the Kali Linux ISO file.Open VirtualBox, click New, enter "Kali Linux", select Type: Linux and Version: Debian (64-bit).  
2. Set RAM to at least 4GB ,Set disk storage to at least 30GB, choose Dynamically Allocated or Fixed Size, and create the VM. 
3. Go to Settings > Storage, click Empty under Controller: IDE. 
4. Select Graphical Install, follow the prompts to set language, location, username, and password.
5. Choose Partitioning Method (Guided - Use Entire Disk) and wait for installation to complete.


### **Step 3: Install Sleuth Kit (CLI-based Forensic Tools)**
🔗 **Download Sleuth Kit**: [Click Here](https://sleuthkit.org/download.php)  

### **Installation Steps:**
1. Download the **Windows ZIP package** from the official website.  
2. Extract the ZIP folder and move it to a suitable directory (e.g., `C:\sleuthkit`).  
3. Add the **bin folder** to Windows PATH:
   - Open **Control Panel** → **System** → **Advanced System Settings**.  
   - Click **Environment Variables** → Edit **Path**.  
   - Add the Sleuth Kit `bin` folder path and save changes.  
4. Verify installation by running:
   ```sh
   fls -version
   
## PROGRAM:

## OUTPUT:
**VIRTUAL BOX:**
<img width="1104" height="779" alt="1" src="https://github.com/user-attachments/assets/0a8cd724-a9b0-4982-83e3-0d58fddd68bb" />
<img width="1144" height="799" alt="2" src="https://github.com/user-attachments/assets/8079a648-1098-4dfb-80d9-227f6f8688f7" />
<img width="1195" height="789" alt="3" src="https://github.com/user-attachments/assets/b7bd12e9-62b3-4ac9-acdc-c37381e7aebd" />
<img width="1032" height="623" alt="4" src="https://github.com/user-attachments/assets/19a32726-a8b4-47e7-9b34-b63d2f547d2d" />

**KALI LINUX:**
<img width="1207" height="715" alt="5" src="https://github.com/user-attachments/assets/0451f9af-ea7f-458b-a120-f20fe38da8a6" />
<img width="1286" height="775" alt="6" src="https://github.com/user-attachments/assets/0dbf4229-2a23-46e0-bc75-eb64c25f6826" />
<img width="1222" height="573" alt="7" src="https://github.com/user-attachments/assets/07b5e261-2af6-4c3b-b465-0ab83f7a4361" />
<img width="1294" height="771" alt="8" src="https://github.com/user-attachments/assets/b286db93-1369-4207-ace2-81ecefaff114" />
<img width="1290" height="752" alt="9" src="https://github.com/user-attachments/assets/030f8629-f073-434d-bf75-262ad0911695" />

**SLEUTH-KIT:**
<img width="1477" height="754" alt="Screenshot 2025-08-18 111631" src="https://github.com/user-attachments/assets/b0434ae5-879c-458b-84da-cd84d59bef92" />



## RESULT:
The setup and installation of VMware, Kali Linux, and Sleuth Kit was completed successfully.

The setup and installation of VMware, Kali Linux, and Sleuth Kit was completed successfully.
