# Enhanced-CSO-MEC-Task-Offloading
Enhanced Chameleon Swarm Optimization for MEC Task Offloading - Results &amp; Code

This repository contains experimental results for:

**"Enhanced Chameleon Swarm Optimization for Task Offloading in Mobile Edge Computing with Interdependent Computations"**

**Authors:** Chandra Shaker Arrabotu, Anita J P  
**Submitted to:** IEEE ACCESS (February 2026)

---

## 📊 Data Availability

## Files

### `performance_metrics.csv` 
Raw experimental results from 30 independent runs.

**Columns:**
- Algorithm, Run, Fitness, Latency (ms), Energy (J), CPU Utilization (%)

**Records:** 180 rows (30 runs × 6 algorithms)

### `statistical_analysis.csv` 
Statistical comparison results for all algorithms.

**Columns:**
- Mean ± Std for all metrics
- t-statistic, p-value, Improvement (%)
- Cohen's d effect size, Significance flag

**Records:** 6 rows (1 per algorithm)

**Key Results:**
- Enhanced CSO vs Standard CSO: 57.12% improvement, p < 0.001, d = -2.39
- All comparisons highly significant (p < 0.000001)
- All effect sizes large (|d| > 1.6)

### Currently Available:
✅ **Raw Experimental Data** (`data/performance_metrics.csv`)
- 30 independent runs × 6 algorithms
- Metrics: Fitness, Latency, Energy, CPU Utilization

**Statistical Validation:**
- All comparisons: p < 0.000001
- Effect sizes: |d| > 1.6 (large)
- 30 independent runs per algorithm

### Coming After Acceptance:
⏳ Source code implementations  
⏳ Visualization figures  
⏳ Detailed experimental report  
⏳ Statistical analysis scripts  

---

## 📖 Citation
If you use this data or code, please cite:
```bibtex
@article{arrabotu2026enhanced,
  title={Enhanced Chameleon Swarm Optimization for Task Offloading 
         in Mobile Edge Computing with Interdependent Computations},
  author={Arrabotu, Chandra Shaker and Anita, J P},
  journal={IEEE ACCESS (submitted)},
  year={2026}
}
```

---

## 📧 Contact

**Chandra Shaker Arrabotu**  
Amrita School of Engineering, Coimbatore  
Email: a_chandrashaker@cb.students.amrita.edu

**Corresponding Author: Anita J P**  
Email: jp_anita@cb.amrita.edu

---

## 📄 License

MIT License

---

**Last Updated:** February 2026  
**Status:** Data available | Full code and analysis coming after paper acceptance
