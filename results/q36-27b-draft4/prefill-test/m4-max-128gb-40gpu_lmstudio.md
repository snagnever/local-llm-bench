# Apple M4 Max / 128GB / 40 GPU cores

**Model:** q36-27b-draft4  
**Backend:** lmstudio  
**Scenario:** prefill-test (single-shot)  

| Turn | Context | Prefill | Gen | Gen tok/s | Effective tok/s | Total | Output |
|-----:|--------:|--------:|----:|----------:|----------------:|------:|-------:|
| 1 | 655 | 4.11s | 8.56s | 11.9 | **8.1** | 12.67s | 102 |
| 2 | 1,453 | 8.51s | 11.54s | 12.2 | **7.0** | 20.05s | 141 |
| 3 | 3,015 | 17.48s | 13.42s | 11.1 | **4.8** | 30.91s | 149 |
| 4 | 8,496 | 70.33s | 14.12s | 10.4 | **1.7** | 84.45s | 147 |

**Total prefill:** 100.4s  
**Total generation:** 47.6s  
**Total time:** 148.1s  
**Avg generation tok/s:** 11.4  
**Avg effective tok/s:** 3.6  
