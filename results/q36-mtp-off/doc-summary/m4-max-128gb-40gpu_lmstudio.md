# Apple M4 Max / 128GB / 40 GPU cores

**Model:** q36-mtp-off  
**Backend:** lmstudio  
**Scenario:** doc-summary (single-shot)  

| Turn | Context | Prefill | Gen | Gen tok/s | Effective tok/s | Total | Output |
|-----:|--------:|--------:|----:|----------:|----------------:|------:|-------:|
| 1 | 425 | 0.58s | 1.71s | 76.5 | **57.1** | 2.30s | 131 |
| 2 | 612 | 0.46s | 1.18s | 76.4 | **55.0** | 1.64s | 90 |
| 3 | 535 | 0.58s | 1.29s | 75.7 | **52.2** | 1.88s | 98 |
| 4 | 524 | 0.55s | 1.55s | 75.4 | **55.6** | 2.10s | 117 |
| 5 | 1,518 | 1.35s | 1.18s | 76.2 | **35.5** | 2.54s | 90 |

**Total prefill:** 3.5s  
**Total generation:** 6.9s  
**Total time:** 10.4s  
**Avg generation tok/s:** 76.0  
**Avg effective tok/s:** 50.3  
