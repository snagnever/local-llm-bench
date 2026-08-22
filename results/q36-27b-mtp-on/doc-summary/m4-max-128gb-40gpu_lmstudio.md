# Apple M4 Max / 128GB / 40 GPU cores

**Model:** q36-27b-mtp-on  
**Backend:** lmstudio  
**Scenario:** doc-summary (single-shot)  

| Turn | Context | Prefill | Gen | Gen tok/s | Effective tok/s | Total | Output |
|-----:|--------:|--------:|----:|----------:|----------------:|------:|-------:|
| 1 | 425 | 2.85s | 4.19s | 23.4 | **13.9** | 7.05s | 98 |
| 2 | 612 | 2.55s | 4.45s | 20.2 | **12.9** | 7.00s | 90 |
| 3 | 535 | 2.86s | 3.22s | 23.6 | **12.5** | 6.08s | 76 |
| 4 | 524 | 2.85s | 5.32s | 22.2 | **14.5** | 8.16s | 118 |
| 5 | 1,518 | 7.36s | 4.72s | 20.3 | **7.9** | 12.08s | 96 |

**Total prefill:** 18.5s  
**Total generation:** 21.9s  
**Total time:** 40.4s  
**Avg generation tok/s:** 21.9  
**Avg effective tok/s:** 11.8  
