# Apple M4 Max / 128GB / 40 GPU cores

**Model:** q36-draft6  
**Backend:** lmstudio  
**Scenario:** doc-summary (single-shot)  

| Turn | Context | Prefill | Gen | Gen tok/s | Effective tok/s | Total | Output |
|-----:|--------:|--------:|----:|----------:|----------------:|------:|-------:|
| 1 | 425 | 0.68s | 1.45s | 74.4 | **50.7** | 2.13s | 108 |
| 2 | 612 | 0.55s | 1.27s | 71.8 | **50.0** | 1.82s | 91 |
| 3 | 535 | 0.68s | 1.40s | 72.4 | **48.7** | 2.08s | 101 |
| 4 | 524 | 0.66s | 1.39s | 72.1 | **48.9** | 2.04s | 100 |
| 5 | 1,518 | 1.50s | 1.40s | 67.8 | **32.7** | 2.90s | 95 |

**Total prefill:** 4.1s  
**Total generation:** 6.9s  
**Total time:** 11.0s  
**Avg generation tok/s:** 71.7  
**Avg effective tok/s:** 45.1  
