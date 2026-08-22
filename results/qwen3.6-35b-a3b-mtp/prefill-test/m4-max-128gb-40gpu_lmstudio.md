# Apple M4 Max / 128GB / 40 GPU cores

**Model:** qwen3.6-35b-a3b-mtp  
**Backend:** lmstudio  
**Scenario:** prefill-test (single-shot)  

| Turn | Context | Prefill | Gen | Gen tok/s | Effective tok/s | Total | Output |
|-----:|--------:|--------:|----:|----------:|----------------:|------:|-------:|
| 1 | 655 | 0.79s | 1.08s | 75.3 | **43.5** | 1.86s | 81 |
| 2 | 1,453 | 1.54s | 1.77s | 71.4 | **38.2** | 3.30s | 126 |
| 3 | 3,015 | 3.18s | 1.36s | 70.0 | **20.9** | 4.54s | 95 |
| 4 | 8,496 | 13.70s | 2.42s | 61.6 | **9.2** | 16.12s | 149 |

**Total prefill:** 19.2s  
**Total generation:** 6.6s  
**Total time:** 25.8s  
**Avg generation tok/s:** 69.6  
**Avg effective tok/s:** 17.5  
