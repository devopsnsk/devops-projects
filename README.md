## 📅 Day 1 Proof
- Created repo and pushed first proof file.  

![Day1 Screenshot](day1/day1-screenshot.png)

## 📅 Day 2 Proof
- Practiced basic Linux commands: pwd, ls, cd, mkdir, touch, echo, cat, cp, mv, rm, rmd  

![Day2 Screenshot](day2/day2-screenshot.png)

## 📅 Day3 Progress

- Practiced **Linux Advanced Commands**
  - User management (`adduser`, `passwd`, `usermod`, `deluser`)
  - Permissions (`chmod`, `chown`, `groups`)
  - File search (`find`, `locate`, `which`, `whereis`)
- Added **day3-proof.txt**  
- Uploaded screenshots of practice.
-  
## 📅 Day 4 Proof
- Practiced Git basics: init, add, commit, branch, checkout, merge, delete branch  

![Day4 Screenshot](day4/day4-screenshot.png)

## 📅 Day5 Progress

- Practiced **Git Merge Conflicts**
  - Created `feature` branch and `main` branch changes
  - Resolved merge conflict in `config.txt`
- Practiced **Docker Basics**
  - Ran `hello-world` container
  - Pulled and ran `nginx` container → verified at `http://localhost:8080`
- Added **day5-proof.txt**  
- Uploaded screenshots of Docker and Git conflict resolution.
- 
- # Day 6 - Docker Cowsay Practice
## Description
This project contains a Dockerfile to run `cowsay` in a container.

## Dockerfile
- Base image: Ubuntu 20.04
- Installed cowsay
- CMD uses `/usr/games/cowsay` for proper execution.
- 
- # **Day7: Docker Compose & Git Branch Practice**

## **Progress Summary**

### **1️⃣ Project Setup**
- Folder created: `~/devops-projects/day7`
- Files included:
  - `docker-compose.yml`
  - `README.md`
  - `html/index.html`
  - Screenshots for proof

---

# Day 8: Jenkins Installation and Setup

## Objective
Install Jenkins on Ubuntu and verify it is running successfully.

## Steps Performed

1. **Install Java (required for Jenkins)**
```bash
sudo apt update
sudo apt install openjdk-17-jdk -y
java -version

# Day 9: Jenkins First Job & Build Pipeline

## Objective
Create a Jenkins job, run a simple build, and verify the build history and console output.

## Steps Performed

1. **Open Jenkins**
   - URL: `http://localhost:8080`
   - Login with admin credentials

2. **Create a New Job**
   - Click **New Item**
   - Enter **Job Name**: `Day9-demo-job`
   - Select **Freestyle project** → Click **OK**

3. **Configure Job**
   - Add a description: `First Jenkins job for Day 9 practice`
   - Scroll to **Build** → Click **Add build step** → **Execute shell**
   - Enter the following shell commands:
     ```bash
     echo "Hello from Day 9 Jenkins job! 🚀"
     date
     ```

4. **Save & Build**
   - Click **Save**
   - Click **Build Now** → Job will start running

5. **Verify Build**
   - Click **#1** under **Build History**
   - Click **Console Output**
   - Expected output:
     ```
     Hello from Day 9 Jenkins job! 🚀
     Wed Oct 08 10:30:00 IST 2025
     ```

## Proof of Completion
- Screenshot saved as: `screenshot_day9.png`
- Jenkins job console output verified
- Build history shows successful run

# 🚀 Day 10 – Jenkins Pipeline Project

## 🎯 Objective
Learned how to create and run a **Jenkins Pipeline job** using a GitHub repository as the SCM (Source Code Management).

---

## 🧩 Steps Performed

1. **Created Jenkins Pipeline Job**
   - Opened Jenkins dashboard → New Item → Selected **Pipeline** → Named it `Day10-Pipeline`.
   
2. **Configured Pipeline Script from SCM**
   - Selected: **Pipeline script from SCM**
   - SCM: **Git**
   - Repository URL: `https://github.com/devopsnsk/devops-projects`
   - Branch: `main`
   - Script Path: `Jenkinsfile`

3. **Created Jenkinsfile in Repo**
   - Added pipeline stages:
     - Clone repository  
     - Build stage  
     - Test stage  
     - Deploy stage  

4. **Triggered Job**
   - Job fetched code from GitHub and executed stages successfully.

---

## 🧠 Learning
- Understood **Jenkinsfile structure** (stages, steps, agents).
- Learned how **SCM integration** works between Jenkins and GitHub.
- Practiced troubleshooting “Jenkinsfile not found” errors.

---

## 📸 Screenshot Proof
![Day 10 Screenshot](./screenshot_day10.png)


Day 11 – Jenkins + GitHub Webhook Integration
🎯 Goal
Integrate Jenkins with GitHub so that every commit automatically triggers a Jenkins build.

🧠 Concepts Learned
Webhook setup in GitHub
Jenkins Git integration
Automatic build trigger (CI)
Jenkins log verification
⚙️ Steps Followed
Created Jenkins pipeline job linked with GitHub repo.
Generated GitHub personal access token (PAT).
Configured credentials in Jenkins.
Set up webhook in GitHub → Settings → Webhooks → Add webhook.
Payload URL: http://<your-public-jenkins-URL>/github-webhook/
Content type: application/json
Tested automatic build trigger by pushing a new commit.
Verified Jenkins build started automatically.
---

## ✅ Outcome
Successfully created and executed a Jenkins Pipeline job using a GitHub repository.


