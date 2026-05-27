# Comparative Study of PWA Caching Strategies

## 📄 Research Paper

This repository contains a simulation-based comparative study evaluating Progressive Web Application (PWA) caching and synchronization strategies in low-connectivity environments.

---

## 🎓 Title

Evaluation of Offline-First Progressive Web Application Caching and Synchronization Strategies for Emergency Alerts in Low-Connectivity Environments

---

## 🎯 Overview

This study investigates and compares two Progressive Web Application (PWA) caching and synchronization strategies under different network conditions:

- Cache-First with Instant Synchronization  
- Stale-While-Revalidate (SWR) with Background Synchronization  

The evaluation is conducted under the following simulated network environments:
- 2G (low connectivity)
- 3G (moderate connectivity)
- Offline (no connectivity)

The goal is to determine which strategy provides better reliability and performance for emergency alert systems in low-connectivity environments.

---

## 🧪 Methodology

A Design Science Research (DSR) and simulation-based approach was used to evaluate system performance.

### Experimental Setup:
- Browser-based simulation using Chrome DevTools network throttling
- Android Emulator (simulated mid-range device environment)
- Node.js local server environment
- Minimum of 30 simulation runs per configuration

### Statistical Analysis:
- ANOVA (Analysis of Variance)
- Bonferroni-adjusted pairwise comparisons
- IBM SPSS Statistics v29

---

## 🛠 Tools & Technologies Used

- Progressive Web Applications (PWA)
- Service Workers (Cache-First & Stale-While-Revalidate strategies)
- IndexedDB (offline storage handling)
- Chrome DevTools (network simulation: 2G, 3G, Offline)
- Android Emulator (device environment simulation)
- Node.js (local development environment)
- Microsoft Excel (data aggregation and metric preparation)
- IBM SPSS Statistics (ANOVA and statistical testing)

---

## 📊 Evaluation Metrics

The following performance metrics were used:

- Cache Hit Ratio  
- Synchronization Latency  
- Offline Submission Success Rate  

---

## 🔍 Key Findings

- Cache-First with Instant Synchronization performs best in fully offline environments due to higher reliability and cache dependency.
- Stale-While-Revalidate (SWR) performs better under partial connectivity (2G/3G) due to background synchronization efficiency.
- System performance is highly dependent on network conditions, confirmed through statistically significant interaction effects (ANOVA results).
- A trade-off exists between data freshness (SWR) and reliability (Cache-First).

---

## 📁 Full Research Paper

📄 [Download Full Paper](./pwa-caching-comparative-study.pdf)

---

## 📌 Contribution

This study provides empirical evidence for selecting appropriate Progressive Web Application caching and synchronization strategies for emergency communication systems in low-connectivity environments. It supports the design of more reliable and resilient offline-first systems for critical alert delivery.

---

## 👨‍🎓 Author

Ayush Premchand  
Durban University of Technology 
