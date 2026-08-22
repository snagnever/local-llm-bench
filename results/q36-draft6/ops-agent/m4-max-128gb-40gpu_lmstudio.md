# Apple M4 Max / 128GB / 40 GPU cores

**Model:** q36-draft6  
**Backend:** lmstudio  
**Scenario:** ops-agent (conversation)  

| Turn | Context | Prefill | Gen | Gen tok/s | Effective tok/s | Total | Output |
|-----:|--------:|--------:|----:|----------:|----------------:|------:|-------:|
| 1 | 575 | 0.89s | 4.15s | 49.2 | **40.5** | 5.04s | 204 |
| 2 | 1,004 | 1.15s | 4.24s | 50.0 | **39.4** | 5.39s | 212 |
| 3 | 1,306 | 1.45s | 4.54s | 45.4 | **34.4** | 5.99s | 206 |
| 4 | 1,730 | 1.89s | 3.34s | 50.9 | **32.5** | 5.22s | 170 |
| 5 | 2,142 | 2.39s | 5.53s | 51.2 | **35.8** | 7.92s | 283 |
| 6 | 2,682 | 2.82s | 3.89s | 67.2 | **38.9** | 6.70s | 261 |
| 7 | 3,012 | 3.22s | 5.47s | 47.9 | **30.1** | 8.69s | 262 |
| 8 | 3,473 | 3.63s | 6.44s | 54.1 | **34.6** | 10.07s | 348 |

**Total prefill:** 17.4s  
**Total generation:** 37.6s  
**Total time:** 55.0s  
**Avg generation tok/s:** 52.0  
**Avg effective tok/s:** 35.4  
