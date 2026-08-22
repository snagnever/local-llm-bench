# Apple M4 Max / 128GB / 40 GPU cores

**Model:** qwen3.6-35b-a3b-ud-mlx  
**Backend:** lmstudio  
**Scenario:** creative-writing (single-shot)  

| Turn | Context | Prefill | Gen | Gen tok/s | Effective tok/s | Total | Output |
|-----:|--------:|--------:|----:|----------:|----------------:|------:|-------:|
| 1 | 57 | 0.17s | 4.19s | 99.6 | **95.6** | 4.36s | 417 |
| 2 | 60 | 0.15s | 7.62s | 98.4 | **96.4** | 7.77s | 749 |
| 3 | 58 | 0.15s | 4.56s | 98.3 | **95.2** | 4.71s | 448 |

**Total prefill:** 0.5s  
**Total generation:** 16.4s  
**Total time:** 16.8s  
**Avg generation tok/s:** 98.8  
**Avg effective tok/s:** 95.9  
