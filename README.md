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



