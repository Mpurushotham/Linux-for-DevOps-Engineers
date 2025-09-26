# Day 4 – Process Management

**Goal:** Handle running processes

---

### Before you begin
Run some long processes (sleep, tail).

---

### What it is
Processes = running programs, managed via ps, top, kill.

---

### Why it matters (DevOps)
Keeps CI/CD agents healthy and prevents resource hogs.

---

### Real-life Analogy
Think of orchestra: each instrument (process) must be managed.

---

### Example Commands / Script
```bash
ps aux | grep nginx
kill -9 <pid>
top
htop
```

🔎 Breakdown:  
ps=process list, kill=terminate, top=interactive view.

---

### Diagram
```
[CPU] → [Processes]
       ↘ top/htop monitor
```

---

### DevOps Scenario
Build agent overloaded → identify and kill rogue process.

---

### Hands-on Exercise
Run sleep 500, find pid, kill it, confirm.

---

### Reflection Questions
- Why use SIGTERM before SIGKILL?
