# US-ETF-Asset-Allocation-Research

### 作者: Eric Hsu
### 日期: 2023.05.15

### 考慮在以下幾檔ETF中做資產配置，並比較和S&P 500 ETF Buy and Hold
ETF: 'XLB', 'XLE', 'XLF', 'XLI', 'XLK', 'XLP', 'XLU', 'XLV', 'XLY'

### 先研究一下ETF 走勢:
![image](https://github.com/EricHsu10/US-ETF-Asset-Allocation-Research/assets/111495932/965a75dc-6698-45b1-bee2-6eb13f3de5ac)

### 嘗試Min Risk資產配置組合:
考慮動能效應，以前三個月ETF平均月報酬做為未來一個月預期月報酬，並以Min Risk做為資產配置考量，建構投資組合。
![image](https://github.com/EricHsu10/US-ETF-Asset-Allocation-Research/assets/111495932/baba8756-c752-4da0-b1fb-2d0af798edb8)
投資組合績效並未優於SPY B&H 策略。

### 考慮以下兩種改進方式:
1. 平均分配權重投資所有ETF。
2. 加入10年期美國公債，做效率前緣資產配置。

意即:更新資產配置最佳化問題

### 方法1: Equal Weight資產配置策略
平均分配資金投入於所有ETF。
![image](https://github.com/EricHsu10/US-ETF-Asset-Allocation-Research/assets/111495932/ffa4ee69-9603-4ac7-95af-13962a9cfb93)
結果: 投資組合績效優於於SPY B&H 策略。

### 方法2: 加入10年期美國公債，做效率前緣資產配置
並新增選擇ETF條件:

每次重新資產配置時，僅考慮前3個月平均月報酬前五名之ETF做為更新資產配置考慮。其他排名在前5以後資產配置設為0。
![image](https://github.com/EricHsu10/US-ETF-Asset-Allocation-Research/assets/111495932/a3e71dcd-0fc3-497e-8aed-d6a2332a6895)
結果: 投資組合績效優於於SPY B&H 策略。

### To Do List
1. 考慮其他方式資產配置，ex. 機器學習方法。
2. 加入更多factor，ex. Fama-French三因子模型。

