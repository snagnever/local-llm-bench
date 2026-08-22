# Apple M4 Max / 128GB / 40 GPU cores

**Model:** qwen3.6-27b-mtp  
**Backend:** lmstudio  
**Scenario:** prefill-test (single-shot)  

| Turn | Context | Prefill | Gen | Gen tok/s | Effective tok/s | Total | Output |
|-----:|--------:|--------:|----:|----------:|----------------:|------:|-------:|
| 1 | 655 | 4.10s | 4.62s | 18.6 | **9.9** | 8.72s | 86 |
| 2 | 1,453 | 8.23s | 8.40s | 17.7 | **9.0** | 16.63s | 149 |
| 3 | 3,015 | 17.40s | 8.89s | 16.8 | **5.7** | 26.29s | 149 |
| 4 | 8,496 | 69.52s | 8.90s | 16.6 | **1.9** | 78.41s | 148 |

**Total prefill:** 99.2s  
**Total generation:** 30.8s  
**Total time:** 130.1s  
**Avg generation tok/s:** 17.4  
**Avg effective tok/s:** 4.1  
