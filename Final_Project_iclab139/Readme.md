### Final lab 實驗概述

從 RTL 到 APR 完整走過所有流程。

### 實驗評論

在 CPU 會遇到太多想不到的問題所以 Pattern 很重要。

### APR 結果與心得

## APR 心得

與 Lab 11 、 Lab 12 相同但這次需要在 2 周內完成所有的操作，因此在做 Final lab 時需要先測試到所有的 corner case 在做 APR 會是相對有效率的做法最後花了 1 整天研究要如何在 APR 時降低 cycle time 到設計時的時間，同時也花了許多時間在 APR 時降低 chip area。

在 cycle time 上如果不在 SRAM 輸出與輸入端加上 REG 在 APR 後的 simulation 可能會出現 setup time violation 或 hold time violation 同時在加大 cycle time 雖然可以解決但並不穩定，最終發現在 SRAM 前後加上 REG 即可解決。

在 APR 時原來使用最初始的方法作但發現面積會很大且在 SRAM 上的繞線非常難繞出來。後來經過討論發現 APR 後的 chip 並沒有特別需要用正方形，且 SRAM 的 I/O 其實可以跟換位置後面積就有縮小 5 萬。

## APR 結果

面積壓縮前 :
![image](https://github.com/wuray890521/IClab_2025_Spring/blob/main/Final_Project_iclab139/final_apr.png)
面積壓縮後 :
![image](https://github.com/wuray890521/IClab_2025_Spring/blob/main/Final_Project_iclab139/2025_spring_final_apr.png)
