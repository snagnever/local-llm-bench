# Apple M4 Max / 128GB / 40 GPU cores

**Model:** q36-draft8  
**Backend:** lmstudio  
**Scenario:** prefill-test (single-shot)  

| Turn | Context | Prefill | Gen | Gen tok/s | Effective tok/s | Total | Output |
|-----:|--------:|--------:|----:|----------:|----------------:|------:|-------:|
| 1 | 655 | 0.86s | 2.16s | 36.5 | **26.1** | 3.02s | 79 |
| 2 | 1,453 | 1.63s | 4.23s | 35.2 | **25.4** | 5.86s | 149 |
| 3 | 3,015 | 3.31s | 2.36s | 36.0 | **15.0** | 5.68s | 85 |
| 4 | 8,496 | 14.16s | 5.43s | 27.4 | **7.6** | 19.59s | 149 |

**Total prefill:** 20.0s  
**Total generation:** 14.2s  
**Total time:** 34.2s  
**Avg generation tok/s:** 33.8  
**Avg effective tok/s:** 13.5  
