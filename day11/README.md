# Day 11 – Jenkins + GitHub Webhook Integration

## 🎯 Goal
Integrate Jenkins with GitHub so that every commit automatically triggers a Jenkins build.

## 🧠 Concepts Learned
- Webhook setup in GitHub
- Jenkins Git integration
- Automatic build trigger (CI)
- Jenkins log verification

## ⚙️ Steps Followed
1. Created Jenkins pipeline job linked with GitHub repo.
2. Generated GitHub personal access token (PAT).
3. Configured credentials in Jenkins.
4. Set up webhook in GitHub → Settings → Webhooks → Add webhook.
   - Payload URL: `http://<your-public-jenkins-URL>/github-webhook/`
   - Content type: `application/json`
5. Tested automatic build trigger by pushing a new commit.
6. Verified Jenkins build started automatically.
