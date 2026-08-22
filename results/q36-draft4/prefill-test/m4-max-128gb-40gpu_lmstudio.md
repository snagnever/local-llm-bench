# Apple M4 Max / 128GB / 40 GPU cores

**Model:** q36-draft4  
**Backend:** lmstudio  
**Scenario:** prefill-test (single-shot)  

| Turn | Context | Prefill | Gen | Gen tok/s | Effective tok/s | Total | Output |
|-----:|--------:|--------:|----:|----------:|----------------:|------:|-------:|
| 1 | 655 | 0.80s | 1.12s | 63.4 | **37.1** | 1.92s | 71 |
| 2 | 1,453 | 1.57s | 2.46s | 60.6 | **37.0** | 4.03s | 149 |
| 3 | 3,015 | 3.21s | 1.95s | 64.2 | **24.2** | 5.16s | 125 |
| 4 | 8,496 | 13.96s | 1.33s | 51.9 | **4.5** | 15.29s | 69 |

**Total prefill:** 19.5s  
**Total generation:** 6.9s  
**Total time:** 26.4s  
**Avg generation tok/s:** 60.0  
**Avg effective tok/s:** 15.7  
