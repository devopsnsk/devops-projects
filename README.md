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
- Uploaded screenshots of practice 
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
- Uploaded screenshots of Docker and Git conflict resolution
- # Day 6 - Docker Cowsay Practice
## Description
This project contains a Dockerfile to run `cowsay` in a container.

## Dockerfile
- Base image: Ubuntu 20.04
- Installed cowsay
- CMD uses `/usr/games/cowsay` for proper execution

## How to Run
```bash
docker build -t sai-docker-demo .
docker run sai-docker-demo /usr/games/cowsay "Docker Day 6 Success!"


# **Day7: Docker Compose & Git Branch Practice**

## **Description**
On **Day 7**, I practiced **Docker Compose**, a tool to define and manage multi-container Docker applications. The project includes:

1. **Web (NGINX)** – Serves a simple HTML page.
2. **Redis** – Lightweight in-memory database.

I ran the containers using `docker compose up -d` and verified both services with `docker ps`. The NGINX service was accessed in a browser at [http://localhost:8081](http://localhost:8081).

Additionally, I practiced **Git branch workflow**:
- Created a feature branch `day7-feature`
- Committed Docker Compose files, HTML page, and proof screenshots
- Pushed branch to GitHub
- Created a Pull Request and merged it into `main`

---

## **Docker Compose Practice**


