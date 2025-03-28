# Surveying and Preserving the Digital Crime Scene

## **Aim:**
Data recovery from unallocated space, using forensic tools(Autospy) to extract and analyze data.

## **Implementation steps:**

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

![](./images/a1.png)

- Enter a **Case Name** (e.g., `Autopsy1`).  
- Choose a **Case Folder** location.  
- Click **Next** → Click **Finish**.  

![](./images/a2.png)

### **Add the Virtual Disk as an Evidence Source**  
- Click **Add Data Source**  → **Select Host**

![](./images/a3.png)

- Select **Local Disk** → **next** 

![](./images/a4.png)

- Select Disk → **Choose the VHD drive (`Drive1`)**

![](./images/a5.png)

- Click **Next** → Keep default settings → Click **Finish**.  
- Wait for Autopsy to process the disk.  

### **Recover Deleted Files**  
- Go to **File Views** (left panel).  

![](./images/a6.png)

![](./images/a7.png)

- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  

![](./images/a8.png)

- Select a folder to see the recovered files (e.g., `C:\forensic`).  
- Image is recovered successfully.


## Output :
### Folder before deleting the files
![Screenshot (174)](https://github.com/user-attachments/assets/92a2e440-c7e2-416a-b3cb-c72fee7f8e0b)


### Folder after deleting the files
![Screenshot (175)](https://github.com/user-attachments/assets/34850831-0c01-4bb4-a641-e8791eb0df13)


### Folder after extracting the deleted images using autopsy

![Screenshot (176)](https://github.com/user-attachments/assets/aca5d752-3a80-4a02-8cce-0a65dac6e1a8)

## Result:
Successfully extracted the deleted files from unallocated space using the Autospy tool.
