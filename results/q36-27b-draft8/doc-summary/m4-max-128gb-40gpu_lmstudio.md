# Apple M4 Max / 128GB / 40 GPU cores

**Model:** q36-27b-draft8  
**Backend:** lmstudio  
**Scenario:** doc-summary (single-shot)  

| Turn | Context | Prefill | Gen | Gen tok/s | Effective tok/s | Total | Output |
|-----:|--------:|--------:|----:|----------:|----------------:|------:|-------:|
| 1 | 425 | 2.91s | 6.51s | 18.7 | **13.0** | 9.42s | 122 |
| 2 | 612 | 2.60s | 6.75s | 15.6 | **11.2** | 9.35s | 105 |
| 3 | 535 | 2.92s | 6.25s | 14.6 | **9.9** | 9.17s | 91 |
| 4 | 524 | 2.90s | 5.51s | 18.0 | **11.8** | 8.41s | 99 |
| 5 | 1,518 | 7.73s | 5.81s | 18.8 | **8.1** | 13.54s | 109 |

**Total prefill:** 19.1s  
**Total generation:** 30.8s  
**Total time:** 49.9s  
**Avg generation tok/s:** 17.1  
**Avg effective tok/s:** 10.5  
