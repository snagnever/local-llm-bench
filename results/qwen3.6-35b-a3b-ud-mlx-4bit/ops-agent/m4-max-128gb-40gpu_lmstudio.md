# Apple M4 Max / 128GB / 40 GPU cores

**Model:** qwen3.6-35b-a3b-ud-mlx  
**Backend:** lmstudio  
**Scenario:** ops-agent (conversation)  

| Turn | Context | Prefill | Gen | Gen tok/s | Effective tok/s | Total | Output |
|-----:|--------:|--------:|----:|----------:|----------------:|------:|-------:|
| 1 | 575 | 0.58s | 2.79s | 95.9 | **79.3** | 3.38s | 268 |
| 2 | 1,084 | 0.59s | 3.46s | 97.0 | **82.9** | 4.05s | 336 |
| 3 | 1,526 | 0.48s | 3.24s | 97.0 | **84.5** | 3.71s | 314 |
| 4 | 2,049 | 0.62s | 2.66s | 98.1 | **79.5** | 3.29s | 261 |
| 5 | 2,561 | 0.66s | 4.33s | 95.9 | **83.3** | 4.98s | 415 |
| 6 | 3,210 | 0.78s | 3.45s | 95.7 | **78.0** | 4.23s | 330 |
| 7 | 3,627 | 0.62s | 2.85s | 96.0 | **78.9** | 3.47s | 274 |
| 8 | 4,117 | 0.67s | 3.38s | 95.1 | **79.3** | 4.05s | 321 |

**Total prefill:** 5.0s  
**Total generation:** 26.2s  
**Total time:** 31.2s  
**Avg generation tok/s:** 96.3  
**Avg effective tok/s:** 80.8  
