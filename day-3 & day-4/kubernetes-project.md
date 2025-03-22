---
marp: true
---

# Setting up minikube and kubectl and deploying a project in kubernetes

**Day - 3 and 4**

<p>24MCR029 <br>
Harikrishnan N </p>

---

##  Setting up minikube: Step 1

<img src="./images/day-3 & day-4/Screenshot (6).png" width="950px">

---

##  Setting up minikube: Step 2

<img src="./images/day-3 & day-4/Screenshot (7).png" width="950px">

---

##  Setting up minikube: Step 3

<img src="./images/day-3 & day-4/Screenshot (8).png" width="950px">

---

##  Setting up kubectl: Step 1 

<img src="./images/day-3 & day-4/Screenshot (9).png" width="950px">

---

##  Setting up kubectl: Step 2 

<img src="./images/day-3 & day-4/Screenshot (10).png" width="950px">

---

##  Setting up kubectl: Step 3 

<img src="./images/day-3 & day-4/Screenshot (11).png" width="950px">

---

##  Setting up kubectl: Step 4 

<img src="./images/day-3 & day-4/Screenshot (12).png" width="950px">

---

##  Kubernetes installation using minikube

<img src="./images/day-3 & day-4/Screenshot (13).png" width="950px">

---

## List kubernetes nodes

<img src="./images/day-3 & day-4/Screenshot (13).png" width="950px">

---

## Setting up environments

<img src="./images/day-3 & day-4/Screenshot (15).png" width="950px">

---

## Building image for backend

<img src="./images/day-3 & day-4/Screenshot (17).png" width="950px">

---

## Loading backend image in kubernetes

<img src="./images/day-3 & day-4/Screenshot (19).png" width="950px">

<p>Just like this, load the frontend:latest image</p>

---

## Building image for frontend

<img src="./images/day-3 & day-4/Screenshot (22).png" width="950px">

---

## Applying k8s configurations

<img src="./images/day-3 & day-4/Screenshot (24).png" width="950px">

---

## Running frontend services inside a pod

<img src="./images/day-3 & day-4/Screenshot (26).png" width="950px">

---

## Running backend services inside a pod

<img src="./images/day-3 & day-4/Screenshot (28).png" width="950px">

---

## Frontend service and backend service can be seen inside a browser

<img src="./images/day-3 & day-4/Screenshot (28).png" width="900px">

---
<p>The fetch request moves to failed state as we are running the servies in wsl. Due to windows firewall and windows defender, accessing resources from an unknown http url is restricted</p>
---

_End of day 3 and 4 assignment_