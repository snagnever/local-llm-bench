# Apple M4 Max / 128GB / 40 GPU cores

**Model:** q36-draft3  
**Backend:** lmstudio  
**Scenario:** doc-summary (single-shot)  

| Turn | Context | Prefill | Gen | Gen tok/s | Effective tok/s | Total | Output |
|-----:|--------:|--------:|----:|----------:|----------------:|------:|-------:|
| 1 | 425 | 0.62s | 0.88s | 93.7 | **54.7** | 1.50s | 82 |
| 2 | 612 | 0.49s | 1.18s | 76.4 | **53.9** | 1.67s | 90 |
| 3 | 535 | 0.63s | 0.94s | 90.2 | **54.0** | 1.57s | 85 |
| 4 | 524 | 0.59s | 1.04s | 98.0 | **62.3** | 1.64s | 102 |
| 5 | 1,518 | 1.44s | 1.08s | 85.0 | **36.5** | 2.52s | 92 |

**Total prefill:** 3.8s  
**Total generation:** 5.1s  
**Total time:** 8.9s  
**Avg generation tok/s:** 88.7  
**Avg effective tok/s:** 50.7  
