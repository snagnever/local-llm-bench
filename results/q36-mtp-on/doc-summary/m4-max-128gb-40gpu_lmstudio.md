# Apple M4 Max / 128GB / 40 GPU cores

**Model:** q36-mtp-on  
**Backend:** lmstudio  
**Scenario:** doc-summary (single-shot)  

| Turn | Context | Prefill | Gen | Gen tok/s | Effective tok/s | Total | Output |
|-----:|--------:|--------:|----:|----------:|----------------:|------:|-------:|
| 1 | 425 | 0.60s | 1.29s | 100.0 | **68.1** | 1.90s | 129 |
| 2 | 612 | 0.48s | 0.91s | 91.4 | **59.8** | 1.39s | 83 |
| 3 | 535 | 0.60s | 1.15s | 86.3 | **56.5** | 1.75s | 99 |
| 4 | 524 | 0.59s | 1.21s | 92.0 | **61.9** | 1.79s | 111 |
| 5 | 1,518 | 1.42s | 1.03s | 93.6 | **39.2** | 2.45s | 96 |

**Total prefill:** 3.7s  
**Total generation:** 5.6s  
**Total time:** 9.3s  
**Avg generation tok/s:** 92.7  
**Avg effective tok/s:** 55.9  
