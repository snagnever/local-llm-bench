# Apple M4 Max / 128GB / 40 GPU cores

**Model:** q36-27b-draft6  
**Backend:** lmstudio  
**Scenario:** prefill-test (single-shot)  

| Turn | Context | Prefill | Gen | Gen tok/s | Effective tok/s | Total | Output |
|-----:|--------:|--------:|----:|----------:|----------------:|------:|-------:|
| 1 | 655 | 4.03s | 10.21s | 9.5 | **6.8** | 14.24s | 97 |
| 2 | 1,453 | 8.58s | 17.40s | 8.5 | **5.7** | 25.98s | 148 |
| 3 | 3,015 | 18.20s | 20.70s | 7.2 | **3.8** | 38.91s | 149 |
| 4 | 8,496 | 71.03s | 19.37s | 7.6 | **1.6** | 90.40s | 147 |

**Total prefill:** 101.8s  
**Total generation:** 67.7s  
**Total time:** 169.5s  
**Avg generation tok/s:** 8.2  
**Avg effective tok/s:** 3.2  
