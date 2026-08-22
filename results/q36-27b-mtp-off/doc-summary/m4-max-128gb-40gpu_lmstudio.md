# Apple M4 Max / 128GB / 40 GPU cores

**Model:** q36-27b-mtp-off  
**Backend:** lmstudio  
**Scenario:** doc-summary (single-shot)  

| Turn | Context | Prefill | Gen | Gen tok/s | Effective tok/s | Total | Output |
|-----:|--------:|--------:|----:|----------:|----------------:|------:|-------:|
| 1 | 425 | 2.84s | 5.27s | 17.3 | **11.2** | 8.11s | 91 |
| 2 | 612 | 2.52s | 5.87s | 17.2 | **12.0** | 8.39s | 101 |
| 3 | 535 | 2.82s | 6.30s | 17.2 | **11.8** | 9.12s | 108 |
| 4 | 524 | 2.82s | 6.29s | 17.2 | **11.8** | 9.12s | 108 |
| 5 | 1,518 | 7.30s | 6.07s | 17.1 | **7.8** | 13.37s | 104 |

**Total prefill:** 18.3s  
**Total generation:** 29.8s  
**Total time:** 48.1s  
**Avg generation tok/s:** 17.2  
**Avg effective tok/s:** 10.6  
