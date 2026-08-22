# Apple M4 Max / 128GB / 40 GPU cores

**Model:** qwen3.6-35b-a3b-mtp  
**Backend:** lmstudio  
**Scenario:** ops-agent (conversation)  

| Turn | Context | Prefill | Gen | Gen tok/s | Effective tok/s | Total | Output |
|-----:|--------:|--------:|----:|----------:|----------------:|------:|-------:|
| 1 | 575 | 0.75s | 2.96s | 79.3 | **63.3** | 3.71s | 235 |
| 2 | 1,038 | 1.09s | 2.87s | 76.4 | **55.3** | 3.96s | 219 |
| 3 | 1,357 | 1.41s | 2.25s | 81.2 | **49.9** | 3.67s | 183 |
| 4 | 1,761 | 1.80s | 2.74s | 80.3 | **48.5** | 4.54s | 220 |
| 5 | 2,210 | 2.24s | 4.71s | 81.6 | **55.3** | 6.95s | 384 |
| 6 | 2,830 | 2.92s | 2.33s | 98.0 | **43.5** | 5.25s | 228 |
| 7 | 3,126 | 3.19s | 3.83s | 75.8 | **41.3** | 7.02s | 290 |
| 8 | 3,614 | 3.62s | 5.71s | 82.5 | **50.5** | 9.33s | 471 |

**Total prefill:** 17.0s  
**Total generation:** 27.4s  
**Total time:** 44.4s  
**Avg generation tok/s:** 81.9  
**Avg effective tok/s:** 50.2  
