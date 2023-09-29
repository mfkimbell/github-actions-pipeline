# github-actions-pipeline

The goal of this project was to gain a basic understanding of github actions. This project auto-generates comments on issues created in this repository. One of the comments is generated through a community action, the other is generated through the Github API. 

### How to run
Run `npm install` in the webapp folder, then `npm run dev` 

### **Tools Used:**
* `React` For rendering jsx elements and creating UI
* `Npm` Package management and frontend server management
* `Vite` Unit testing and running the React server (as opposed to using "Create React App")
* `GithubActions` Automation and CI/CD Pipeline management

---

### Basic workflow for auto-generating comments as a reaction to comments and github api usage:

<img width="862" alt="Screenshot 2023-09-20 at 11 22 17 PM" src="https://github.com/mfkimbell/github-actions-pipeline/assets/107063397/7f8883b8-d671-4fec-a165-30818e97cb80">

---

### Unit tests for React App through Vite locally:

<img width="566" alt="Screenshot 2023-09-28 at 2 29 48 PM" src="https://github.com/mfkimbell/github-actions-pipeline/assets/107063397/7d2bf780-d11e-4ee0-b1a9-40de2bf35595">

### Unit tests run with Actions:
<img width="736" alt="Screenshot 2023-09-28 at 3 43 51 PM" src="https://github.com/mfkimbell/github-actions-pipeline/assets/107063397/1e83f325-7b20-416d-b6b5-756d3f4cda59">

---

### Blocking changes unless there has at least 1 approval:
<img width="842" alt="Screenshot 2023-09-28 at 2 48 13 PM" src="https://github.com/mfkimbell/github-actions-pipeline/assets/107063397/c8400e29-ec4e-4af2-90d9-19d5aa67f4f0">
