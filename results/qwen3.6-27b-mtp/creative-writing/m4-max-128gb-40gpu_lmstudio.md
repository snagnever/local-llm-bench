# Apple M4 Max / 128GB / 40 GPU cores

**Model:** qwen3.6-27b-mtp  
**Backend:** lmstudio  
**Scenario:** creative-writing (single-shot)  

| Turn | Context | Prefill | Gen | Gen tok/s | Effective tok/s | Total | Output |
|-----:|--------:|--------:|----:|----------:|----------------:|------:|-------:|
| 1 | 57 | 0.89s | 29.49s | 15.0 | **14.6** | 30.37s | 442 |
| 2 | 60 | 0.90s | 50.00s | 16.0 | **15.7** | 50.90s | 799 |
| 3 | 58 | 1.15s | 26.08s | 15.0 | **14.4** | 27.23s | 391 |

**Total prefill:** 2.9s  
**Total generation:** 105.6s  
**Total time:** 108.5s  
**Avg generation tok/s:** 15.3  
**Avg effective tok/s:** 15.0  
