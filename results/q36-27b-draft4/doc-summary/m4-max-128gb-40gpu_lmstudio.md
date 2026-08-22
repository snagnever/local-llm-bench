# Apple M4 Max / 128GB / 40 GPU cores

**Model:** q36-27b-draft4  
**Backend:** lmstudio  
**Scenario:** doc-summary (single-shot)  

| Turn | Context | Prefill | Gen | Gen tok/s | Effective tok/s | Total | Output |
|-----:|--------:|--------:|----:|----------:|----------------:|------:|-------:|
| 1 | 425 | 2.84s | 7.42s | 16.6 | **12.0** | 10.27s | 123 |
| 2 | 612 | 2.54s | 5.17s | 13.9 | **9.3** | 7.71s | 72 |
| 3 | 535 | 2.86s | 5.62s | 14.4 | **9.5** | 8.48s | 81 |
| 4 | 524 | 2.85s | 6.53s | 15.8 | **11.0** | 9.38s | 103 |
| 5 | 1,518 | 7.61s | 5.88s | 17.0 | **7.4** | 13.48s | 100 |

**Total prefill:** 18.7s  
**Total generation:** 30.6s  
**Total time:** 49.3s  
**Avg generation tok/s:** 15.5  
**Avg effective tok/s:** 9.7  
