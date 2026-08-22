# Apple M4 Max / 128GB / 40 GPU cores

**Model:** q36-draft6  
**Backend:** lmstudio  
**Scenario:** prefill-test (single-shot)  

| Turn | Context | Prefill | Gen | Gen tok/s | Effective tok/s | Total | Output |
|-----:|--------:|--------:|----:|----------:|----------------:|------:|-------:|
| 1 | 655 | 0.84s | 2.25s | 44.5 | **32.4** | 3.08s | 100 |
| 2 | 1,453 | 1.55s | 3.34s | 44.6 | **30.4** | 4.89s | 149 |
| 3 | 3,015 | 3.30s | 3.50s | 42.3 | **21.8** | 6.80s | 148 |
| 4 | 8,496 | 14.15s | 3.81s | 39.1 | **8.3** | 17.96s | 149 |

**Total prefill:** 19.8s  
**Total generation:** 12.9s  
**Total time:** 32.7s  
**Avg generation tok/s:** 42.6  
**Avg effective tok/s:** 16.7  
