# 📘 Red Hat EX188 – Containers & Podman Certification Prep

This repository documents the **exam objectives**, **competencies**, and conceptual understanding required to pass the **Red Hat EX188: Red Hat Certified Specialist in Containers** exam.  
The structure and objectives presented here reflect real-world tasks and the practical skills evaluated during the exam.

---

## 🎯 Overview of the EX188 Exam

The Red Hat EX188 exam validates your ability to:

- Manage containers using **Podman**
- Build, run, configure, and troubleshoot containerized applications
- Create and manage **Containerfiles (Dockerfiles)**
- Work effectively with container networking, volumes, and registries
- Deploy multi-container applications
- Build and push custom images with environment variables and arguments

This is a **hands-on, performance-based exam**, and success depends on strong understanding of container fundamentals and their application under exam conditions.

---

# 🧩 EX188 Exam Objective Areas

Below are the key domains and conceptual objectives tested on the EX188 exam.

---

## **1️⃣ Running Simple Containers**

### **Aim**
Evaluate your ability to run containerized applications using correct parameters and configurations.

### **Key Understanding Required**
- Selecting and pulling container images  
- Running containers in detached/background mode  
- Mapping host ports to container ports  
- Mounting local files or directories into containers  
- Naming and managing container lifecycle  

### **Why This Matters**
This domain tests the foundational container management skills required to deploy services quickly and reliably.

---

## **2️⃣ Interacting With Running Containers**

### **Aim**
Assess your ability to modify or configure active containers without stopping them.

### **Key Understanding Required**
- Copying content (files or directories) into containers  
- Replacing or updating default configurations  
- Executing commands inside a running container  
- Reloading or refreshing application services  
- Ensuring updated content becomes available immediately  

### **Why This Matters**
Real DevOps workflows often require adjustments on live containers. This objective validates your operational proficiency.

---

## **3️⃣ Injecting Environment Variables Into Containers**

### **Aim**
Test your ability to configure container behavior using environment variables.

### **Key Understanding Required**
- Setting variables at container runtime  
- Running multiple containers with differing configurations  
- Using environment variables for dynamic application responses  
- Understanding correct port exposure and mapping  

### **Why This Matters**
Environment variables are essential for runtime configuration, secrets handling, and multi-instance deployments.

---

## **4️⃣ Building Custom Container Images**

### **Aim**
Measure your ability to write, modify, and build custom images based on Containerfiles.

### **Key Understanding Required**
- Writing Containerfiles with core instructions (`FROM`, `RUN`, `COPY`, `ARG`, `ENV`, etc.)  
- Using build-time arguments (`ARG`) to parameterize images  
- Mapping build arguments to environment variables  
- Structuring reusable and consistent images  
- Tagging and pushing images to private or remote registries  

### **Why This Matters**
Image creation is central to DevOps automation. This objective ensures you can build reliable, configurable, and production-ready containers.

---

## **5️⃣ Deploying Multi-Container Application Stacks**

### **Aim**
Evaluate your ability to deploy multi-service, interconnected container environments.

### **Key Understanding Required**
- Creating and managing Podman networks  
- Using named volumes for persistent data  
- Deploying database, web, and application services as separate containers  
- Passing correct environment variables for inter-service communication  
- Exposing ports for public and internal access  

### **Why This Matters**
Modern applications consist of multiple components. This objective tests your ability to architect complete container-based solutions.

---

## **6️⃣ Troubleshooting Multi-Container Environments**

### **Aim**
Assess your ability to diagnose and resolve issues within a containerized environment.

### **Key Understanding Required**
- Identifying incorrect network or volume configurations  
- Inspecting and interpreting logs  
- Fixing misconfigured or unhealthy containers  
- Rebuilding container setups when required  
- Ensuring all services run persistently and communicate properly  

### **Why This Matters**
Troubleshooting is a key real-world skill and an essential part of maintaining production container environments.

---

# 🧠 Core Knowledge Required for EX188

Across all objectives, you must be confident with:

### **Container Management**
- Starting, stopping, inspecting, and removing containers  
- Using logs, interactive shells, and exec  

### **Image Management**
- Pulling, tagging, inspecting, removing images  
- Authenticating and pushing to registries  

### **Storage & Persistency**
- Named volumes vs bind mounts  
- Ensuring persistent data across restarts  

### **Networking**
- Creating and inspecting custom networks  
- Port mapping and inter-container connectivity  

### **Containerfiles**
- Building optimized, maintainable container images  
- Using ARG and ENV effectively  
- Setting entrypoints and commands  

### **Multi-Container Architecture**
- Deploying multi-tier apps (DB + backend + frontend)  
- Handling configuration through environment variables  
- Ensuring proper communication between services  

---

# 🏁 Purpose of This Repository

This repository serves as:

- A structured guide for EX188 exam preparation  
- A reference to the full range of exam objectives  
- A conceptual map for hands-on practice environments  
- A foundation for your own container exercises and notes  

By understanding these objectives, you prepare directly for the skills evaluated in the certification exam.

---
