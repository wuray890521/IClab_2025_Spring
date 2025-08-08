### Lab11 實驗概述

1. 使用 Lab 05 的設計做 APR。

### 實驗評論

在做 APR 時主要的電路應該由 RTL 端去控制，因此我認為如果在有限時間內如果 APR 端有出現問題，在 RTL 端解決是相對有效率的解決方法。

### APR 遇到問題

1. 在最後的 post routing 出現的問題可能是在設計中使用 SRAM 時沒有再輸入與輸出訊號都使用 reg 把 SRAM 的數據包起來導致，在完成這個操作後可以將 APR 的 cycle time 下降到與 synthesis 相同。
2. 在做 APR 時 cycle time 應該非常接近 synthesis 如果出現可以檢查是否有哪些操作出問題。
3.

### APR 結果示意圖

![image](https://github.com/wuray890521/IClab_2025_Spring/blob/main/Lab05_iclab139/lab05_apr.png)
