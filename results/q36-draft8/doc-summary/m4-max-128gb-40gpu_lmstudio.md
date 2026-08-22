# Apple M4 Max / 128GB / 40 GPU cores

**Model:** q36-draft8  
**Backend:** lmstudio  
**Scenario:** doc-summary (single-shot)  

| Turn | Context | Prefill | Gen | Gen tok/s | Effective tok/s | Total | Output |
|-----:|--------:|--------:|----:|----------:|----------------:|------:|-------:|
| 1 | 425 | 0.71s | 1.44s | 66.0 | **44.2** | 2.15s | 95 |
| 2 | 612 | 0.58s | 1.65s | 41.2 | **30.4** | 2.23s | 68 |
| 3 | 535 | 0.72s | 2.16s | 44.9 | **33.7** | 2.88s | 97 |
| 4 | 524 | 0.69s | 1.58s | 56.8 | **39.6** | 2.27s | 90 |
| 5 | 1,518 | 1.53s | 1.46s | 58.3 | **28.5** | 2.99s | 85 |

**Total prefill:** 4.2s  
**Total generation:** 8.3s  
**Total time:** 12.5s  
**Avg generation tok/s:** 53.4  
**Avg effective tok/s:** 34.7  
