# Apple M4 Max / 128GB / 40 GPU cores

**Model:** qwen3.6-35b-a3b-mtp  
**Backend:** lmstudio  
**Scenario:** doc-summary (single-shot)  

| Turn | Context | Prefill | Gen | Gen tok/s | Effective tok/s | Total | Output |
|-----:|--------:|--------:|----:|----------:|----------------:|------:|-------:|
| 1 | 425 | 0.60s | 1.35s | 98.8 | **68.2** | 1.95s | 133 |
| 2 | 612 | 0.48s | 0.98s | 88.9 | **59.5** | 1.46s | 87 |
| 3 | 535 | 0.61s | 1.07s | 94.7 | **60.1** | 1.68s | 101 |
| 4 | 524 | 0.58s | 1.01s | 95.5 | **60.7** | 1.60s | 97 |
| 5 | 1,518 | 1.41s | 1.16s | 86.4 | **38.9** | 2.57s | 100 |

**Total prefill:** 3.7s  
**Total generation:** 5.6s  
**Total time:** 9.3s  
**Avg generation tok/s:** 92.9  
**Avg effective tok/s:** 56.0  
