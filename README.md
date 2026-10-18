# day15-kubernet-fundamentals
# Building and Testing My First Local Kubernetes Environment 🚀

## 📝 What is this project?
Instead of just reading about cloud technology, I set up a real, fully-functioning mini data center on my computer. I learned how to launch a website server, monitor its health from behind the scenes, and safely save all of my code tracking changes to GitHub just like professional software engineers do.

---

## 🔥 Step-by-Step Milestones I Completed:

### 1. Started the Mini Cloud Center (Kubernetes)
* **What I did:** I used a tool called **`kind`** to build a localized Kubernetes cluster on my virtual machine.
* **Why it matters:** This created a smart ecosystem that can run, manage, and automatically heal software applications.

### 2. Verified the Infrastructure (Nodes)
* **What I did:** I checked the main engine room of my cluster to ensure the server nodes were active and `Ready`.
* **Why it matters:** This proved the foundation was solid before launching any apps.

### 3. Launched and Inspected the Website (Deployments & Pods)
* **What I did:** I deployed a website server (Nginx) and checked on the "Pods" (the tiny containers running the actual website).
* **Why it matters:** I verified that the app was built correctly and running smoothly in its isolated space.

### 4. Read the Cluster History and Server Logs (Events & Logs)
* **What I did:** I investigated the cluster's internal timeline ("Events") to see how it was built, and I looked at the live "Logs" (the raw terminal output) of my running website containers.
* **Why it matters:** This taught me how to read the server's mind to troubleshoot issues, check for errors, and verify that the app is listening to traffic.

### 5. Saved My Work to the Cloud (Git Push)
* **What I did:** After everything worked perfectly, I bundled all my configuration code scripts and safely pushed them up to my remote repository on GitHub.
* **Why it matters:** This ensures my project is backed up safely, version-controlled, and ready to share with the engineering community.

---

## 🛠️ The Simple Tech Stack I Used:
* **Kubernetes (`kind`)** – The automated system that keeps the website alive.
* **Kubectl** – The command controller I used to talk to Kubernetes.
* **Git & GitHub** – The tracking system used to save and backup my project.
* **Nginx** – The website engine running inside my cluster.
