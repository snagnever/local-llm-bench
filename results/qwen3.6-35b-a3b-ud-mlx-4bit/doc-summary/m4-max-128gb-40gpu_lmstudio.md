# Apple M4 Max / 128GB / 40 GPU cores

**Model:** qwen3.6-35b-a3b-ud-mlx  
**Backend:** lmstudio  
**Scenario:** doc-summary (single-shot)  

| Turn | Context | Prefill | Gen | Gen tok/s | Effective tok/s | Total | Output |
|-----:|--------:|--------:|----:|----------:|----------------:|------:|-------:|
| 1 | 425 | 0.45s | 1.45s | 96.0 | **73.2** | 1.90s | 139 |
| 2 | 612 | 0.42s | 0.76s | 95.5 | **61.4** | 1.19s | 73 |
| 3 | 535 | 0.52s | 0.99s | 97.2 | **63.7** | 1.51s | 96 |
| 4 | 524 | 0.49s | 1.08s | 96.4 | **66.4** | 1.57s | 104 |
| 5 | 1,518 | 1.04s | 0.96s | 97.0 | **46.6** | 2.00s | 93 |

**Total prefill:** 2.9s  
**Total generation:** 5.2s  
**Total time:** 8.2s  
**Avg generation tok/s:** 96.4  
**Avg effective tok/s:** 61.9  
