# Task 8 - Java Maven Build with Jenkins

## 📌 Objective
The goal of this task is to learn how to use Jenkins to build a simple Java application using Maven — a first step into Continuous Integration (CI).

---

## 🛠 Tools Used
- Java JDK 8
- Apache Maven 3.8.6
- Jenkins (via Docker)
- Git

---

## 📁 Project Structure
hello-java-maven/
├── pom.xml
└── src/
└── main/
└── java/
└── HelloWorld.java


---

## 🧪 Steps Performed

1. Created a simple Java app: `HelloWorld.java`
2. Created a `pom.xml` for Maven build configuration
3. Started Jenkins using Docker
4. Configured Maven inside Jenkins (Manage Jenkins → Global Tool Configuration)
5. Created a **Freestyle Project** in Jenkins
6. Configured the job to run Maven goal: `clean package`
7. Built the job and verified successful output (`BUILD SUCCESS`)

---

## ✅ Output Screenshot
> _Attached in the repo_ → `build-success-screenshot.png`

---

## 🙋 What I Learned
- How to run a Maven build using Jenkins
- How to create and configure a Jenkins Freestyle job
- Basics of CI/CD with Jenkins and Maven

---

## 📌 Author
**Yasvanth Rajan E**  
DevOps Internship Task 8 Submission  


