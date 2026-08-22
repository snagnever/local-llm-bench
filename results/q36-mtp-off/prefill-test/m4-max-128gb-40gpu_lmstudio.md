# Apple M4 Max / 128GB / 40 GPU cores

**Model:** q36-mtp-off  
**Backend:** lmstudio  
**Scenario:** prefill-test (single-shot)  

| Turn | Context | Prefill | Gen | Gen tok/s | Effective tok/s | Total | Output |
|-----:|--------:|--------:|----:|----------:|----------------:|------:|-------:|
| 1 | 655 | 0.73s | 1.59s | 75.0 | **51.4** | 2.31s | 119 |
| 2 | 1,453 | 1.46s | 1.49s | 75.2 | **38.0** | 2.94s | 112 |
| 3 | 3,015 | 3.00s | 1.32s | 73.4 | **22.4** | 4.32s | 97 |
| 4 | 8,496 | 13.05s | 1.64s | 67.9 | **7.6** | 14.68s | 111 |

**Total prefill:** 18.2s  
**Total generation:** 6.0s  
**Total time:** 24.3s  
**Avg generation tok/s:** 72.9  
**Avg effective tok/s:** 18.1  
