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

![Screenshot 2025-03-26 152949](https://github.com/user-attachments/assets/0c77a5c6-54be-40a3-b8d1-0d741d247930)


![Screenshot 2025-03-26 153241](https://github.com/user-attachments/assets/639d003d-52f7-4058-8a8c-07d0c16d6b5f)


- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  

![Screenshot 2025-03-26 153241](https://github.com/user-attachments/assets/d763920a-9487-46da-b437-752f120dfa3c)


- Select a folder to see the recovered files (e.g., `C:\forensic`).  
- Image is recovered successfully.


## Output :
### Folder before deleting the files
![Screenshot 2025-03-26 153312](https://github.com/user-attachments/assets/b820ec5a-7c48-4414-9a5b-31a3d74356ef)


### Folder after deleting the files
![Screenshot 2025-03-26 160433](https://github.com/user-attachments/assets/fa06894e-d8fc-4c16-b8bc-101504ada8da)


### Folder after extracting the deleted images using autopsy
![Screenshot 2025-03-26 160359](https://github.com/user-attachments/assets/3b564a64-5edd-44ae-8e11-4a9ee7f5d070)


## Result:
Successfully extracted the deleted files from unallocated space using the Autospy tool.
