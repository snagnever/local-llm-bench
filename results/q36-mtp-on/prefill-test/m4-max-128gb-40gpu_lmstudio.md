# Apple M4 Max / 128GB / 40 GPU cores

**Model:** q36-mtp-on  
**Backend:** lmstudio  
**Scenario:** prefill-test (single-shot)  

| Turn | Context | Prefill | Gen | Gen tok/s | Effective tok/s | Total | Output |
|-----:|--------:|--------:|----:|----------:|----------------:|------:|-------:|
| 1 | 655 | 0.78s | 1.49s | 79.7 | **52.4** | 2.27s | 119 |
| 2 | 1,453 | 1.54s | 1.85s | 68.8 | **37.5** | 3.39s | 127 |
| 3 | 3,015 | 3.19s | 1.91s | 72.4 | **27.1** | 5.10s | 138 |
| 4 | 8,496 | 13.79s | 2.36s | 63.1 | **9.2** | 16.15s | 149 |

**Total prefill:** 19.3s  
**Total generation:** 7.6s  
**Total time:** 26.9s  
**Avg generation tok/s:** 71.0  
**Avg effective tok/s:** 19.8  
