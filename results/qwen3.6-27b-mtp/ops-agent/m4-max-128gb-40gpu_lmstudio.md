# Apple M4 Max / 128GB / 40 GPU cores

**Model:** qwen3.6-27b-mtp  
**Backend:** lmstudio  
**Scenario:** ops-agent (conversation)  

| Turn | Context | Prefill | Gen | Gen tok/s | Effective tok/s | Total | Output |
|-----:|--------:|--------:|----:|----------:|----------------:|------:|-------:|
| 1 | 575 | 3.99s | 9.48s | 17.3 | **12.2** | 13.47s | 164 |
| 2 | 978 | 5.53s | 11.52s | 18.9 | **12.8** | 17.05s | 218 |
| 3 | 1,300 | 7.20s | 9.65s | 18.0 | **10.3** | 16.85s | 174 |
| 4 | 1,678 | 9.38s | 8.66s | 18.9 | **9.1** | 18.05s | 164 |
| 5 | 2,091 | 11.69s | 20.03s | 18.9 | **11.9** | 31.72s | 378 |
| 6 | 2,697 | 15.40s | 8.34s | 20.6 | **7.2** | 23.74s | 172 |
| 7 | 2,958 | 16.66s | 13.67s | 17.0 | **7.7** | 30.33s | 232 |
| 8 | 3,382 | 19.07s | 18.02s | 18.1 | **8.8** | 37.09s | 327 |

**Total prefill:** 88.9s  
**Total generation:** 99.4s  
**Total time:** 188.3s  
**Avg generation tok/s:** 18.5  
**Avg effective tok/s:** 9.7  
