# 💼 DevOps Interview Questions – Accenture Focused

### ✅ 0. Tell Me About Yourself

**Answer:**

> I am a DevOps Engineer with __X years__ of experience working on CI/CD automation, cloud infrastructure (AWS), and container orchestration using Docker and Kubernetes.  
> My expertise spans across tools like Git, Jenkins, SonarQube, Maven, Terraform, and monitoring with Prometheus and Grafana.  
> In my last project, I worked on setting up a full CI/CD pipeline using Jenkins, integrated SonarQube for code quality, containerized the applications using Docker, and deployed them on a self-managed Kubernetes cluster with Helm charts.  
> I also automated infrastructure provisioning using Terraform on AWS, implementing scalable architecture using EC2, ALB, S3, and RDS.  
> I focus on delivering stable, repeatable deployment pipelines and proactive monitoring to reduce production incidents.

---

###  Linux

**1. How do you monitor and analyze disk I/O performance in Linux during high server load?**  
**2. What’s your troubleshooting approach when a server is unresponsive but pingable via SSH?**  
**3. Write a shell script to archive logs older than 7 days and send an alert if disk usage exceeds 90%.**

---

###  Git

**4. How do you resolve a Git merge conflict during Jenkins automated deployment?**  
**5. What is the difference between `git revert` and `git reset`? Where did you use them in a real-time issue?**  
**6. Explain your Git branching strategy in a microservices-based CI/CD pipeline.**

---

###  Jenkins

**7. How did you implement pipeline-as-code in Jenkins for a multi-module Maven project?**  
**8. In your CI/CD pipeline, how do you handle rollbacks when a deployment fails in Jenkins?**  
**9. Explain the use of `agent`, `stages`, and `post` blocks in a Jenkins declarative pipeline.**

---

###  Docker

**10. What steps did you take when a Docker container was running but the application inside was not accessible?**  
**11. How do you optimize Docker images for faster build and push in CI/CD?**  
**12. Explain the real-time use of Docker Compose in your project for local development or integration testing.**

---

###  Kubernetes

**13. What was the cause and solution when a pod remained in `Pending` state in your cluster?**  
**14. How do you manage dynamic configuration updates in a running Kubernetes application?**  
**15. What’s the difference between `liveness` and `readiness` probes? How did you configure them in your project?**  
**16. Explain the use of `Horizontal Pod Autoscaler (HPA)` in your production environment.**

---

###  AWS + Terraform

**17. How do you manage EC2 auto-scaling and ALB integration using Terraform modules?**  
**18. What is the purpose of using remote backend in Terraform, and how did you implement it in AWS (e.g., S3 + DynamoDB)?**  
**19. In a real project, how did you ensure Terraform changes are reviewed and approved before apply?**  
**20. What is the difference between `terraform plan`, `terraform apply`, and `terraform destroy`? Where did you automate these in CI/CD?**

---
