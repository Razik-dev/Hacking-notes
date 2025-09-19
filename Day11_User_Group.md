# 👥 Day 11 – User & Group Management  

## 📅 Date: 11/09/2025  

### 🔹 Commands Learned  

#### User Management  
- `whoami` → show current logged-in user  
📸 ![whoami](images/day11_whoami.png)  

- `id` → show user ID (UID) and groups  
📸 ![id](images/day11_id.png)  

- `adduser testuser` → create new user  
📸 ![adduser](images/day11_adduser.png)  

- `passwd testuser` → set/change password for user  
📸 ![passwd](images/day11_passwd.png)  

- `deluser testuser` → delete user  
📸 ![deluser](images/day11_deluser.png)  

---

#### Group Management  
- `groups` → show groups of current user  
📸 ![groups](images/day11_groups.png)  

- `groupadd testgroup` → create new group  
📸 ![groupadd](images/day11_groupadd.png)  

- `usermod -aG testgroup testuser` → add user to group  
📸 ![usermod](images/day11_usermod.png)  

- `gpasswd -d testuser testgroup` → remove user from group  
📸 ![gpasswd](images/day11_gpasswd.png)  

---

#### Checking Users & Groups  
- `cat /etc/passwd | tail` → list system users  
📸 ![passwdfile](images/day11_passwdfile.png)  

- `cat /etc/group | tail` → list groups  
📸 ![groupfile](images/day11_groupfile.png)  

---

### 🔹 Key Learnings  
1. Each user has a **UID** and belongs to one or more groups.  
2. Groups make it easy to manage **permissions for multiple users**.  
3. `adduser` / `deluser` helps manage accounts, while `passwd` changes passwords.  
4. The `/etc/passwd` and `/etc/group` files store user & group details.  

---

### 🔹 Next Steps  
Tomorrow → **Day 12: Permissions in Depth (ACL, umask)**.  

---

### 🔖 Suggested commit message  
`Day 11 – User & Group Management`
