# 📦 Day 10 – Archiving & Compression

## 📅 Date: 18/09/2025  

### 🔹 Commands Learned  

#### Archiving with `tar`  
- `tar -cvf archive.tar file1 file2` → create archive  
📸 ![tar create](images/day10_tar_create.png)  

- `tar -xvf archive.tar` → extract archive  
📸 ![tar extract](images/day10_tar_extract.png)  

- `tar -tvf archive.tar` → list files in archive  
📸 ![tar list](images/day10_tar_list.png)  

---

#### Compression  
- `gzip file1` → compress file1 → file1.gz  
📸 ![gzip](images/day10_gzip.png)  

- `gunzip file1.gz` → decompress  
📸 ![gunzip](images/day10_gunzip.png)  

- `bzip2 file1` → compress using bzip2  
📸 ![bzip2](images/day10_bzip2.png)  

- `bunzip2 file1.bz2` → decompress  
📸 ![bunzip2](images/day10_bunzip2.png)  

---

#### Working with `.zip`  
- `zip archive.zip file1 file2` → create zip file  
📸 ![zip](images/day10_zip.png)  

- `unzip archive.zip` → extract zip file  
📸 ![unzip](images/day10_unzip.png)  

---

### 🔹 Key Learnings  
1. **tar** = archive multiple files into one.  
2. **gzip/bzip2** = compress single files (smaller size).  
3. **zip/unzip** = widely used for compression + archiving (cross-platform).  
4. Useful for **backups, transferring tools, CTF challenges**.  

---

### 🔹 Next Steps  
Tomorrow → **Day 11: User & Group Management** (adduser, passwd, groups).  

---

### 🔖 Suggested commit message  
`Day 10 – Archiving & Compression`
