# Apple M4 Max / 128GB / 40 GPU cores

**Model:** qwen3.6-27b-mtp  
**Backend:** lmstudio  
**Scenario:** doc-summary (single-shot)  

| Turn | Context | Prefill | Gen | Gen tok/s | Effective tok/s | Total | Output |
|-----:|--------:|--------:|----:|----------:|----------------:|------:|-------:|
| 1 | 425 | 2.78s | 5.74s | 22.5 | **15.1** | 8.52s | 129 |
| 2 | 612 | 2.60s | 2.87s | 23.0 | **12.1** | 5.47s | 66 |
| 3 | 535 | 3.07s | 4.24s | 21.7 | **12.6** | 7.31s | 92 |
| 4 | 524 | 2.92s | 6.23s | 21.7 | **14.7** | 9.15s | 135 |
| 5 | 1,518 | 7.45s | 5.14s | 19.6 | **8.0** | 12.59s | 101 |

**Total prefill:** 18.8s  
**Total generation:** 24.2s  
**Total time:** 43.0s  
**Avg generation tok/s:** 21.7  
**Avg effective tok/s:** 12.2  
