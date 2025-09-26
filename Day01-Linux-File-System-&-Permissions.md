# Day 1 – Linux File System & Permissions

**Goal:** Understand Linux file system structure and permissions

---

### Before you begin
Use a Linux VM; run `man hier`.

---

### What it is
Linux organizes files into `/` hierarchy with permissions (rwx) controlling access.

---

### Why it matters (DevOps)
Prevents deployment errors, enforces least privilege in DevOps pipelines.

---

### Real-life Analogy
Apartment keys → Owner (you), Group (roommates), Others (visitors).

---

### Example Commands / Script
```bash
ls -l /etc/passwd
chmod 640 deploy.sh
chown devops:developers deploy.sh
chmod +t /tmp
```

🔎 Breakdown:  
Shows permissions, changes mode, ownership, and sticky bit.

---

### Diagram
```
/ → etc, var, home, tmp tree diagram
```

---

### DevOps Scenario
Ansible copies configs into `/etc/nginx`, wrong ownership → Nginx fails.

---

### Hands-on Exercise
Create file, restrict perms, test as another user, adjust group rights.

---

### Reflection Questions
- What risks if sshd_config is 777? How does Docker volume inherit perms?
