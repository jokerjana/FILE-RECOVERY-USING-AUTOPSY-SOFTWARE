# Using-the-Autopsy-retrieve-the-deleted-files
### Name : JANARTHANAN B
### Reg No: 212223100014
## AIM:
To use Autopsy in Kali Linux to retrieve and analyze deleted files from a disk image.

## DESIGN STEPS:
### Step 1:
Open Autopsy and create a new case with appropriate case details.

### Step 2:
Add a disk image as a data source and let Autopsy analyze the content.

### Step 3:
Navigate to the "Deleted Files" section in Autopsy and examine or recover the deleted files.

## PROGRAM:
### **1. Copy Files to the Virtual Disk**  
- Open **File Explorer** → Go to the new drive (`C: or D:`), where the folder created in the New Virtual Disk
- Create a new folder (`Autospy`) and copy **images or files** into it.  

### **2. Delete the Files**  
- Select any one or two images → Press **Delete**.  
- Empty the **Recycle Bin** to permanently delete them.  

### **3. Recover Deleted Files Using Autopsy**  
### **Open Autopsy & Create a New Case** 

- Launch **Autopsy** and **Run as a administrator**  
- Click **Create New Case**.  

![dfdi1](https://github.com/user-attachments/assets/f654bd06-10fe-4f99-940b-8de796ed8024)

- Enter a **Case Name** (e.g., `Autopsy1`).  
- Choose a **Case Folder** location.  
- Click **Next** → Click **Finish**.  
![dfdi2](https://github.com/user-attachments/assets/add84cc9-66ba-48e8-9a3a-bf078f9b6b43)



### **Add the Virtual Disk as an Evidence Source**  
- Click **Add Data Source**  → **Select Host**


![dfdi3](https://github.com/user-attachments/assets/934da0c2-6fc6-4166-937d-78fce3c18617)


- Select **Local Disk** → **next** 

![dfdi4](https://github.com/user-attachments/assets/d9589646-8c79-45bc-8d3c-0953af07d3f1)


- Select Disk → **Choose the VHD drive (`Drive1`)**

![dfdi5](https://github.com/user-attachments/assets/6e8a0655-b707-491a-902e-c4908d96bc01)


- Click **Next** → Keep default settings → Click **Finish**.  
- Wait for Autopsy to process the disk.  

### **Recover Deleted Files**  
- Go to **File Views** (left panel).  



![a6](https://github.com/user-attachments/assets/f7063263-697f-485f-ad92-ccb0e8a17552)


- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  



- Select a folder to see the recovered files (e.g., `C:\forensic`).  
- Image is recovered successfully.
![dfdi6](https://github.com/user-attachments/assets/de8d34bb-c084-4137-8039-dca5622ad450)


## Output :
### Folder before deleting the files
<img width="1610" height="994" alt="Screenshot 2026-03-23 212453" src="https://github.com/user-attachments/assets/b50e7fa1-4250-4e05-9e1c-700e3b42a535" />


### Folder after deleting the files
<img width="1621" height="926" alt="Screenshot 2026-03-23 212619" src="https://github.com/user-attachments/assets/76603c0c-d2a6-4641-a46e-1fa95137b625" />


### Folder after extracting the deleted images using autopsy
<img width="1901" height="1012" alt="Screenshot 2026-03-23 212923" src="https://github.com/user-attachments/assets/5a9a5ae2-168c-407a-a4d9-ebe2f778fb5b" />

<img width="1666" height="983" alt="Screenshot 2026-03-23 213055" src="https://github.com/user-attachments/assets/254ad288-ee46-4e09-a078-5919876ae0d6" />


## RESULT:
Deleted files were successfully retrieved and analyzed using Autopsy.
github
