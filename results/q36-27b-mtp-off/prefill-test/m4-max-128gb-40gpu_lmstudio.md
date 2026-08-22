# Apple M4 Max / 128GB / 40 GPU cores

**Model:** q36-27b-mtp-off  
**Backend:** lmstudio  
**Scenario:** prefill-test (single-shot)  

| Turn | Context | Prefill | Gen | Gen tok/s | Effective tok/s | Total | Output |
|-----:|--------:|--------:|----:|----------:|----------------:|------:|-------:|
| 1 | 655 | 3.92s | 6.12s | 17.3 | **10.6** | 10.03s | 106 |
| 2 | 1,453 | 7.97s | 8.81s | 16.9 | **8.9** | 16.79s | 149 |
| 3 | 3,015 | 16.95s | 9.03s | 16.5 | **5.7** | 25.98s | 149 |
| 4 | 8,496 | 69.53s | 9.14s | 16.2 | **1.9** | 78.66s | 148 |

**Total prefill:** 98.4s  
**Total generation:** 33.1s  
**Total time:** 131.5s  
**Avg generation tok/s:** 16.7  
**Avg effective tok/s:** 4.2  
