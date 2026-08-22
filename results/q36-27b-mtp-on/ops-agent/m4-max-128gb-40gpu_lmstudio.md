# Apple M4 Max / 128GB / 40 GPU cores

**Model:** q36-27b-mtp-on  
**Backend:** lmstudio  
**Scenario:** ops-agent (conversation)  

| Turn | Context | Prefill | Gen | Gen tok/s | Effective tok/s | Total | Output |
|-----:|--------:|--------:|----:|----------:|----------------:|------:|-------:|
| 1 | 575 | 3.89s | 7.29s | 19.2 | **12.5** | 11.18s | 140 |
| 2 | 947 | 5.23s | 11.65s | 18.7 | **12.9** | 16.88s | 218 |
| 3 | 1,243 | 6.79s | 9.07s | 19.6 | **11.2** | 15.86s | 178 |
| 4 | 1,621 | 9.02s | 7.47s | 18.7 | **8.5** | 16.49s | 140 |
| 5 | 2,005 | 11.28s | 12.59s | 18.3 | **9.6** | 23.87s | 230 |
| 6 | 2,466 | 14.20s | 5.14s | 23.4 | **6.2** | 19.34s | 120 |
| 7 | 2,691 | 15.14s | 12.78s | 17.4 | **8.0** | 27.92s | 222 |
| 8 | 3,113 | 17.46s | 17.81s | 17.5 | **8.8** | 35.27s | 312 |

**Total prefill:** 83.0s  
**Total generation:** 83.8s  
**Total time:** 166.8s  
**Avg generation tok/s:** 19.1  
**Avg effective tok/s:** 9.4  
