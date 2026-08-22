# Apple M4 Max / 128GB / 40 GPU cores

**Model:** q36-27b-draft3  
**Backend:** lmstudio  
**Scenario:** doc-summary (single-shot)  

| Turn | Context | Prefill | Gen | Gen tok/s | Effective tok/s | Total | Output |
|-----:|--------:|--------:|----:|----------:|----------------:|------:|-------:|
| 1 | 425 | 2.97s | 5.26s | 18.4 | **11.8** | 8.23s | 97 |
| 2 | 612 | 2.50s | 3.44s | 17.2 | **9.9** | 5.94s | 59 |
| 3 | 535 | 2.84s | 5.13s | 17.0 | **10.9** | 7.97s | 87 |
| 4 | 524 | 2.85s | 4.80s | 18.3 | **11.5** | 7.65s | 88 |
| 5 | 1,518 | 7.61s | 5.50s | 16.0 | **6.7** | 13.11s | 88 |

**Total prefill:** 18.8s  
**Total generation:** 24.1s  
**Total time:** 42.9s  
**Avg generation tok/s:** 17.4  
**Avg effective tok/s:** 9.8  
