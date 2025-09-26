# Day 5 – System Monitoring

**Goal:** Check system performance

---

### Before you begin
Have top and free installed.

---

### What it is
Monitor CPU, RAM, disk usage.

---

### Why it matters (DevOps)
Helps debug slow pipelines and optimize infra costs.

---

### Real-life Analogy
Like dashboard of your car: speed, fuel, temperature.

---

### Example Commands / Script
```bash
uptime
free -h
df -h
vmstat 1
```

🔎 Breakdown:  
uptime=load avg, free=memory, df=disk, vmstat=cpu/mem IO.

---

### Diagram
```
[Server] → CPU | RAM | Disk → Monitored via CLI
```

---

### DevOps Scenario
K8s node high load → check system metrics before scaling.

---

### Hands-on Exercise
Check memory usage, disk space; simulate with stress tool.

---

### Reflection Questions
- How to decide when to scale based on load averages?
