# JMeter with Jenkins CI/CD

## 📌 Project Overview

This project demonstrates Continuous Integration using Apache JMeter and Jenkins. The JMeter test is executed automatically from Jenkins, and the Performance Plugin is used to publish performance reports.

---

## 🎯 Objective

- Create a JMeter Test Plan
- Execute using Jenkins
- Publish Performance Report
- Analyze Performance Trends

---

## 🛠️ Tools Used

- Apache JMeter 5.6.3
- Jenkins
- Jenkins Performance Plugin
- Java
- Git
- GitHub

---

## Project Workflow

```
JMeter Test Plan
       ↓
Jenkins Job
       ↓
Execute JMeter
       ↓
Generate JTL File
       ↓
Publish Performance Report
```

---

## Jenkins Command

```bash
jmeter -Jjmeter.save.saveservice.output_format=xml -n -t "JMeterWithJenkinsCICD.jmx" -l "JenkinsCICD.jtl"
```

---

## Features

- Automated Performance Testing
- Jenkins Integration
- XML Result Generation
- Performance Trend Analysis

---

## Learning Outcome

- Jenkins Freestyle Project
- Build Steps
- Post Build Actions
- Performance Plugin
- Continuous Integration

---

## 👨‍💻 Author

**Naveen Pandey**
