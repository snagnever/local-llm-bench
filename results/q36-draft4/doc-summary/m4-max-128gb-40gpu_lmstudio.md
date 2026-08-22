# Apple M4 Max / 128GB / 40 GPU cores

**Model:** q36-draft4  
**Backend:** lmstudio  
**Scenario:** doc-summary (single-shot)  

| Turn | Context | Prefill | Gen | Gen tok/s | Effective tok/s | Total | Output |
|-----:|--------:|--------:|----:|----------:|----------------:|------:|-------:|
| 1 | 425 | 0.62s | 1.20s | 72.3 | **47.6** | 1.83s | 87 |
| 2 | 612 | 0.51s | 1.20s | 81.1 | **57.0** | 1.70s | 97 |
| 3 | 535 | 0.65s | 1.06s | 79.0 | **49.2** | 1.71s | 84 |
| 4 | 524 | 0.61s | 0.95s | 82.1 | **49.8** | 1.57s | 78 |
| 5 | 1,518 | 1.45s | 1.45s | 73.8 | **36.9** | 2.90s | 107 |

**Total prefill:** 3.8s  
**Total generation:** 5.9s  
**Total time:** 9.7s  
**Avg generation tok/s:** 77.7  
**Avg effective tok/s:** 46.7  
