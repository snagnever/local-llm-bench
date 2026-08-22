# Apple M4 Max / 128GB / 40 GPU cores

**Model:** qwen3.6-35b-a3b-ud-mlx  
**Backend:** lmstudio  
**Scenario:** prefill-test (single-shot)  

| Turn | Context | Prefill | Gen | Gen tok/s | Effective tok/s | Total | Output |
|-----:|--------:|--------:|----:|----------:|----------------:|------:|-------:|
| 1 | 655 | 0.59s | 0.74s | 106.0 | **59.0** | 1.34s | 79 |
| 2 | 1,453 | 1.06s | 1.17s | 97.9 | **51.3** | 2.22s | 114 |
| 3 | 3,015 | 2.33s | 1.02s | 100.3 | **30.5** | 3.35s | 102 |
| 4 | 8,496 | 9.98s | 1.68s | 87.6 | **12.6** | 11.66s | 147 |

**Total prefill:** 14.0s  
**Total generation:** 4.6s  
**Total time:** 18.6s  
**Avg generation tok/s:** 97.9  
**Avg effective tok/s:** 23.8  
