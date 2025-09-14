# ACH System Performance Testing with JMeter

## 📌 Project Overview
This project demonstrates end-to-end **performance testing** conducted on an Automated Clearing House (ACH) system using **Apache JMeter**.  
The primary focus was to evaluate **system stability, scalability, and bottlenecks** under different workloads.

---

## 🎯 Objectives
- **Load Testing** → Validate system stability under expected traffic.
- **Stress Testing** → Push system beyond normal limits to find breaking points.
- **Bottleneck Analysis** → Identify performance constraints affecting throughput.

---

## 🛠️ Tools & Technologies
- **Apache JMeter** (test scripting & execution)  
- **CSV/HTML reports** for result analysis  
- **Graphs ** for visualization  

---

## 📊 Test Scenarios & Findings

### 🔹 Load Testing
- **Scenario** → Simulated steady login traffic.  
- **Result** → System handled *1 login per second* without performance degradation.  

### 🔹 Stress Testing
- **Scenario** → Increased transaction rate until failure thresholds.  
- **Result** → Sustained *3 transactions per second* with a peak of *9 transactions in 3 seconds* before error rates increased.  

### 🔹 Bottleneck Analysis
- **Scenario** → Multiple concurrent logins tested.  
- **Result** → Bottleneck identified: only *1 user could log in per second* before slowdown.  

---

## 📈 Outcome
The test results provided valuable insights into:
- System **capacity and breaking points**  
- Areas for **optimization and scaling**  
- Data-driven recommendations for improving **reliability and concurrency**  

---
