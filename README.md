# Install-Autopsy-and-Analyze-the-Disk-File-and-Folder-Configuration
# NAME: MOHAN S
# REGISTER NUMBER: 212223240094

## AIM:
To install Autopsy on Kali Linux and analyze disk images, files, and folder configurations for digital forensic purposes.

## DESIGN STEPS:
### Step 1:
Install Autopsy using the terminal with the command:

### Step 2:
Launch Autopsy from the terminal or application menu and create a new case.

### Step 3:
Add a disk image or file to the case and analyze the contents such as deleted files, metadata, and folder structure.

## INSTALLATION PROCEDURE:
### Step1:Download Autopsy
• Visit Autopsy Official Website and download the latest version.

• Double-click the downloaded file and follow the on-screen instructions.
![Screenshot 2025-04-23 094542](https://github.com/user-attachments/assets/d5af4fb4-c7af-4a4c-86f5-e74efed0416d)

## **Implementation steps:**

### **1. Copy Files to the Virtual Disk**  
- Open **File Explorer** → Go to the new drive (`D:`), where the folder created in the New Virtual Disk
- Create a new folder or use the entire disk and then copy **images or files** into it.  

### **2. Delete the Files**  
- Select any one or two images → Press **Delete**.  
- Empty the **Recycle Bin** to permanently delete them.  

### **3. Recover Deleted Files Using Autopsy**  
### **Open Autopsy & Create a New Case** 

- Launch **Autopsy** and **Run as a administrator**  
- Click **Create New Case**.  
![Screenshot 2025-04-23 094100](https://github.com/user-attachments/assets/e5e23cf8-6cce-4a85-84b4-3ce4fb5d9932)



- Enter a **Case Name** (e.g., `Autopsy-1`).  
- Choose a **Case Folder** location.  
- Click **Next** → Click **Finish**.  

![Screenshot (22)](https://github.com/user-attachments/assets/ea7790fc-fc13-4324-a563-1c7c5907c567)

### **Add the Virtual Disk as an Evidence Source**  
- Click **Add Data Source**  → **Select Host**
![Screenshot (23)](https://github.com/user-attachments/assets/141b1819-5249-4e7c-ad54-4c34dca34a40)




- Select **Local Disk** → **next** 
![Screenshot (24)](https://github.com/user-attachments/assets/63cb384b-7f79-4335-bd49-e6836b7e329f)





- Select Disk → **Choose the VHD drive (`New Volume(E:`)**

![Screenshot (25)](https://github.com/user-attachments/assets/04b05304-b685-4109-8659-90a505bfefa7)
- Click **Next** → Keep default settings → Click **Finish**.  
- Wait for Autopsy to process the disk.  


### **Recover Deleted Files**  


- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  


![Screenshot (28)](https://github.com/user-attachments/assets/96e30a5d-43a0-41aa-bc8a-33c65ae7cc18)

## RESULT:
Autopsy was installed successfully and used to analyze disk, file, and folder configuration for forensic investigation.
