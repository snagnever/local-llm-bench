# Apple M4 Max / 128GB / 40 GPU cores

**Model:** q36-27b-draft6  
**Backend:** lmstudio  
**Scenario:** ops-agent (conversation)  

| Turn | Context | Prefill | Gen | Gen tok/s | Effective tok/s | Total | Output |
|-----:|--------:|--------:|----:|----------:|----------------:|------:|-------:|
| 1 | 575 | 4.35s | 26.06s | 9.9 | **8.5** | 30.41s | 259 |
| 2 | 1,046 | 6.25s | 29.79s | 9.9 | **8.2** | 36.04s | 294 |
| 3 | 1,442 | 8.16s | 20.87s | 9.7 | **7.0** | 29.03s | 203 |
| 4 | 1,855 | 10.83s | 33.20s | 9.0 | **6.8** | 44.02s | 300 |
| 5 | 2,417 | 13.45s | 45.98s | 10.1 | **7.8** | 59.44s | 466 |
| 6 | 3,100 | 17.46s | 13.01s | 10.8 | **4.6** | 30.47s | 141 |
| 7 | 3,337 | 18.60s | 29.77s | 8.3 | **5.1** | 48.37s | 246 |
| 8 | 3,787 | 20.77s | 34.52s | 9.2 | **5.7** | 55.29s | 317 |

**Total prefill:** 99.9s  
**Total generation:** 233.2s  
**Total time:** 333.1s  
**Avg generation tok/s:** 9.6  
**Avg effective tok/s:** 6.7  
