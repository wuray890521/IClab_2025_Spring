### Lab12 實驗概述

1. 了解在 APR 時 chip 可能會遇到的問題。
2. 這次的 lab 是使用助教的 design 進行 APR 但其實是用 lab03 的題目做，這次主要解決 IR drop 在 APR 上的問題。

### 實驗評論

在做 APR 時 power 的分析對 APR 的結果也很重要為了避免晶片被燒壞會去分析晶片上所有位置的 power 數值。其中我們可以在 pad 上加上多組 VDD GND 來避免出現 IR drop 的問題。

APR 後的結果在 Lab12_report_iclab139 中。

### APR 結果圖

![image](https://github.com/wuray890521/IClab_2025_Spring/blob/main/Lab12_iclab139/lab12_apr.png)
