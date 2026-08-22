# Apple M4 Max / 128GB / 40 GPU cores

**Model:** q36-draft3  
**Backend:** lmstudio  
**Scenario:** prefill-test (single-shot)  

| Turn | Context | Prefill | Gen | Gen tok/s | Effective tok/s | Total | Output |
|-----:|--------:|--------:|----:|----------:|----------------:|------:|-------:|
| 1 | 655 | 0.81s | 1.21s | 84.6 | **50.5** | 2.02s | 102 |
| 2 | 1,453 | 1.54s | 1.29s | 73.6 | **33.5** | 2.83s | 95 |
| 3 | 3,015 | 3.22s | 1.46s | 67.0 | **20.9** | 4.68s | 98 |
| 4 | 8,496 | 13.87s | 2.13s | 59.2 | **7.9** | 16.00s | 126 |

**Total prefill:** 19.4s  
**Total generation:** 6.1s  
**Total time:** 25.5s  
**Avg generation tok/s:** 71.1  
**Avg effective tok/s:** 16.5  
