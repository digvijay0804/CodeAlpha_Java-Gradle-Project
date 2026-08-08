# Java Application Using Gradle

A simple Java application built and automated using **Gradle**. This project demonstrates Gradle build automation, dependency management, executable JAR creation, Git/GitHub integration, and CI/CD using GitHub Actions.

## 🚀 Project Overview

This project was created as part of a DevOps task to understand how Java applications can be built, tested, and automated using Gradle and GitHub Actions.

## 🛠️ Technologies Used

* Java 21
* Gradle 8.14.4
* JUnit 5
* Git
* GitHub
* GitHub Actions

## 📁 Project Structure

```text
CodeAlpha_Java-Gradle-Project/
├── src/
│   ├── main/
│   │   └── java/
│   │       └── App.java
│   └── test/
│       └── java/
├── .github/
│   └── workflows/
│       └── ci.yml
├── build.gradle
├── settings.gradle
├── gradlew
├── gradlew.bat
├── gradle/
└── .gitignore
```

## ⚙️ Gradle Configuration

The project uses `build.gradle` to configure:

* Java application plugin
* JUnit 5 dependency
* Maven Central repository
* Application main class
* Executable JAR manifest

## 🔧 Build the Application

Clone the repository:

```bash
git clone <YOUR-GITHUB-REPOSITORY-URL>
cd CodeAlpha_Java-Gradle-Project
```

Make the Gradle wrapper executable:

```bash
chmod +x gradlew
```

Build the project:

```bash
./gradlew clean build
```

A successful build will generate the JAR file inside:

```text
build/libs/
```

## ▶️ Run the Application

Run the generated JAR:

```bash
java -jar build/libs/java-gradle-app-1.0.0.jar
```

Expected output:

```text
Hello from Java Gradle Application!
Task 3 - Gradle Build Successful!
```

## 🔄 CI/CD with GitHub Actions

This project uses **GitHub Actions** to automate the Gradle build process.

The workflow performs:

1. Checkout source code
2. Set up Java 21
3. Execute Gradle build
4. Run tests
5. Verify the application build

Workflow file:

```text
.github/workflows/ci.yml
```

Every push to the `main` branch automatically triggers the CI pipeline.

## 🎯 Learning Objectives

* Understand Gradle project structure
* Automate Java application builds
* Manage project dependencies
* Create executable JAR files
* Use Gradle Wrapper
* Integrate Git and GitHub
* Implement CI using GitHub Actions
* Understand basic DevOps automation principles

## ✅ Task Status

**Task 3: Java Application using Gradle — Completed**

* ✅ Java Application
* ✅ Gradle Build Automation
* ✅ Dependency Management
* ✅ Executable JAR
* ✅ GitHub Repository
* ✅ GitHub Actions CI/CD
