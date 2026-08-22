# Apple M4 Max / 128GB / 40 GPU cores

**Model:** qwen3.6-35b-a3b-mtp  
**Backend:** lmstudio  
**Scenario:** creative-writing (single-shot)  

| Turn | Context | Prefill | Gen | Gen tok/s | Effective tok/s | Total | Output |
|-----:|--------:|--------:|----:|----------:|----------------:|------:|-------:|
| 1 | 57 | 0.24s | 7.62s | 68.5 | **66.4** | 7.86s | 522 |
| 2 | 60 | 0.23s | 7.92s | 72.4 | **70.3** | 8.15s | 573 |
| 3 | 58 | 0.24s | 6.12s | 64.9 | **62.4** | 6.36s | 397 |

**Total prefill:** 0.7s  
**Total generation:** 21.7s  
**Total time:** 22.4s  
**Avg generation tok/s:** 68.6  
**Avg effective tok/s:** 66.7  
