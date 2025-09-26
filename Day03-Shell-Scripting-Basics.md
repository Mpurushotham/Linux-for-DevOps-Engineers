# Day 3 – Shell Scripting Basics

**Goal:** Automate tasks with scripts

---

### Before you begin
Open editor nano/vim.

---

### What it is
Scripts are saved commands run as a program.

---

### Why it matters (DevOps)
Automation reduces human error in deployments.

---

### Real-life Analogy
Like writing a cooking recipe once and reusing it.

---

### Example Commands / Script
```bash
#!/bin/bash
echo 'Build started at $(date)'
for f in *.yaml; do kubectl apply -f $f; done
```

🔎 Breakdown:  
Shebang calls bash, echo prints, loop applies YAMLs.

---

### Diagram
```
[script] → [bash] → [execution]
```

---

### DevOps Scenario
Jenkins calls shell script to deploy Kubernetes manifests.

---

### Hands-on Exercise
Write script to create backup dir, copy /etc configs.

---

### Reflection Questions
- How can scripts enforce consistency in deployments?
