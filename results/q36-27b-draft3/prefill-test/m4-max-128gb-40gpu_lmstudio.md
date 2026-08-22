# Apple M4 Max / 128GB / 40 GPU cores

**Model:** q36-27b-draft3  
**Backend:** lmstudio  
**Scenario:** prefill-test (single-shot)  

| Turn | Context | Prefill | Gen | Gen tok/s | Effective tok/s | Total | Output |
|-----:|--------:|--------:|----:|----------:|----------------:|------:|-------:|
| 1 | 655 | 4.23s | 5.65s | 17.2 | **9.8** | 9.87s | 97 |
| 2 | 1,453 | 8.45s | 10.54s | 14.1 | **7.8** | 18.99s | 149 |
| 3 | 3,015 | 17.50s | 11.07s | 12.9 | **5.0** | 28.58s | 143 |
| 4 | 8,496 | 70.71s | 10.83s | 13.6 | **1.8** | 81.54s | 147 |

**Total prefill:** 100.9s  
**Total generation:** 38.1s  
**Total time:** 139.0s  
**Avg generation tok/s:** 14.4  
**Avg effective tok/s:** 3.9  
