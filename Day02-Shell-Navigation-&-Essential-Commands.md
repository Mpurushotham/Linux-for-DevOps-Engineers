# Day 2 – Shell Navigation & Essential Commands

**Goal:** Navigate Linux efficiently

---

### Before you begin
Have a test directory tree ready.

---

### What it is
`pwd`, `ls`, `cd`, `find` help navigate filesystem.

---

### Why it matters (DevOps)
Essential for CI/CD jobs manipulating files and logs.

---

### Real-life Analogy
Like using Google Maps to find your way in a city.

---

### Example Commands / Script
```bash
pwd
ls -lh
cd /var/log
find / -name '*.conf'
```

🔎 Breakdown:  
pwd=show dir, ls=list, cd=change, find=search recursively.

---

### Diagram
```
/home/devops
 ├── project
 └── logs
```

---

### DevOps Scenario
Pipeline script needs to locate logs in /var/logs before uploading to S3.

---

### Hands-on Exercise
Create dirs, navigate, use find to locate files.

---

### Reflection Questions
- What’s faster: manual search or find command?
