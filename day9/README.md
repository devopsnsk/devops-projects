# Day 9: Jenkins First Job & Build Pipeline

## Objective
Create a Jenkins job, run a simple build, and verify build history and console output.

## Steps Performed

1. **Open Jenkins**
- URL: http://localhost:8080
- Login with admin credentials

2. **Create a New Job**
- Click **New Item**
- Job name: Day9-demo-job
- Select **Freestyle project** → Click OK

3. **Configure Job**
- Description: First Jenkins job for Day 9 practice
- Build → Add build step → Execute shell
```bash
echo "Hello from Day 9 Jenkins job! 🚀"
date
```

4. **Save & Build**
- Click **Save**
- Click **Build Now** → Job will run

5. **Verify Build**
- Click **#1** under **Build History**
- Click **Console Output**
- Output example:
```
Hello from Day 9 Jenkins job! 🚀
Wed Oct 08 10:30:00 IST 2025
```

## Proof of Completion
- Screenshot saved as: screenshot day9.png
- Jenkins job console output verified
- Build history shows successful run
