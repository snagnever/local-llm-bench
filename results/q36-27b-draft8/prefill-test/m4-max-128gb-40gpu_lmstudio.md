# Apple M4 Max / 128GB / 40 GPU cores

**Model:** q36-27b-draft8  
**Backend:** lmstudio  
**Scenario:** prefill-test (single-shot)  

| Turn | Context | Prefill | Gen | Gen tok/s | Effective tok/s | Total | Output |
|-----:|--------:|--------:|----:|----------:|----------------:|------:|-------:|
| 1 | 655 | 3.94s | 8.00s | 11.2 | **7.5** | 11.95s | 90 |
| 2 | 1,453 | 8.40s | 10.85s | 11.7 | **6.6** | 19.26s | 127 |
| 3 | 3,015 | 17.66s | 13.07s | 11.4 | **4.8** | 30.73s | 149 |
| 4 | 8,496 | 70.78s | 15.80s | 9.3 | **1.7** | 86.57s | 147 |

**Total prefill:** 100.8s  
**Total generation:** 47.7s  
**Total time:** 148.5s  
**Avg generation tok/s:** 10.9  
**Avg effective tok/s:** 3.5  
