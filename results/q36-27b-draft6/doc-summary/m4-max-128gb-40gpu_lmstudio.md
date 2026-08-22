# Apple M4 Max / 128GB / 40 GPU cores

**Model:** q36-27b-draft6  
**Backend:** lmstudio  
**Scenario:** doc-summary (single-shot)  

| Turn | Context | Prefill | Gen | Gen tok/s | Effective tok/s | Total | Output |
|-----:|--------:|--------:|----:|----------:|----------------:|------:|-------:|
| 1 | 425 | 3.30s | 7.24s | 12.8 | **8.8** | 10.55s | 93 |
| 2 | 612 | 2.68s | 9.88s | 10.2 | **8.0** | 12.56s | 101 |
| 3 | 535 | 2.99s | 6.91s | 11.6 | **8.1** | 9.90s | 80 |
| 4 | 524 | 2.98s | 7.90s | 12.7 | **9.2** | 10.88s | 100 |
| 5 | 1,518 | 7.89s | 7.28s | 13.2 | **6.3** | 15.17s | 96 |

**Total prefill:** 19.8s  
**Total generation:** 39.2s  
**Total time:** 59.1s  
**Avg generation tok/s:** 12.1  
**Avg effective tok/s:** 8.0  
