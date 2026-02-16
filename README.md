# COA-PROJECT
COA PROJECT -ARRAY SIZE AND CACHE MISS ANALYSIS 
![Language](https://img.shields.io/badge/Language-RISC--V%20Assembly-blue)
![Course](https://img.shields.io/badge/Course-Computer%20Organization%20&%20Architecture-orange)
![Simulator](https://img.shields.io/badge/Simulator-Ripes-green)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Platform](https://img.shields.io/badge/Platform-RISC--V-lightgrey)
## 📸 Ripes Simulator Observations

### 🔹 Cache Statistics – Normal Matrix Multiplication
- High number of **compulsory and capacity cache misses**
- Repeated memory accesses cause frequent cache evictions
- Lower cache hit rate due to poor locality

*(Screenshot: Ripes data cache statistics for normal matrix multiplication)*

---

### 🔹 Cache Statistics – Blocked Matrix Multiplication
- Significantly **reduced cache misses**
- Higher cache hit rate due to **blocking (tiling)**
- Improved performance from **temporal and spatial locality**

*(Screenshot: Ripes data cache statistics for blocked matrix multiplication)*

---

### 📊 Comparison Summary
| Method | Cache Hits | Cache Misses |
|------|-----------|-------------|
| Normal Multiplication | Low | High |
| Blocked Multiplication | High | Low |
