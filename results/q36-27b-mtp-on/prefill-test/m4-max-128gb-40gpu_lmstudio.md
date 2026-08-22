# Apple M4 Max / 128GB / 40 GPU cores

**Model:** q36-27b-mtp-on  
**Backend:** lmstudio  
**Scenario:** prefill-test (single-shot)  

| Turn | Context | Prefill | Gen | Gen tok/s | Effective tok/s | Total | Output |
|-----:|--------:|--------:|----:|----------:|----------------:|------:|-------:|
| 1 | 655 | 3.89s | 4.98s | 19.1 | **10.7** | 8.87s | 95 |
| 2 | 1,453 | 8.05s | 8.54s | 17.4 | **9.0** | 16.59s | 149 |
| 3 | 3,015 | 17.17s | 9.12s | 16.3 | **5.7** | 26.30s | 149 |
| 4 | 8,496 | 69.83s | 8.56s | 17.2 | **1.9** | 78.39s | 147 |

**Total prefill:** 98.9s  
**Total generation:** 31.2s  
**Total time:** 130.1s  
**Avg generation tok/s:** 17.5  
**Avg effective tok/s:** 4.1  
