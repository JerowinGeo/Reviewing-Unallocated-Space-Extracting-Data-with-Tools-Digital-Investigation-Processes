# Reviewing-Unallocated-Space-Extracting-Data-with-Tools-Digital-Investigation-Processes

## NAME : JEROWIN GEO J A
## REG NO : 212223100016

## AIM:
To review unallocated space in a disk image, extract data using forensic tools, and understand the digital investigation process.

## DESIGN STEPS:
### Step 1:
Use tools like Autopsy or Sleuth Kit (blkls, icat) to identify and analyze unallocated space.

### Step 2:
Extract data from unallocated space and examine for hidden or deleted content.

### Step 3:
Document and interpret findings as part of the digital investigation process.

## PROGRAM:
Data Extraction and Investigation Tool Usage
```
bash
lsblk
```

```
bash
sudo dd if=/dev/sda of=/home/kali/disk.img bs=512
```

```
bash
mmls ~/disk.img
```
```
bash
sudo ls -lh disk.img
```
```
bash
strings disk.img | less

```

## OUTPUT:
![image](https://github.com/user-attachments/assets/6c2f5c1d-62c7-44ea-bcf7-cf7cb658e59e)
![image](https://github.com/user-attachments/assets/5331e059-fb3f-4937-8a5c-55a93fea5a82)
![image](https://github.com/user-attachments/assets/f6910a59-615b-4d06-9f8c-890cc5aa7139)
![image](https://github.com/user-attachments/assets/55945657-9d53-4867-9ef4-720d768191b8)
![image](https://github.com/user-attachments/assets/41d6ea60-a673-4fdf-9f9f-0f8d66682473)

## RESULT:
The unallocated space was successfully analyzed, data was extracted, and the digital investigation process was followed effectively.


