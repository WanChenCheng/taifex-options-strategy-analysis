# taifex-options-strategy-analysis

[Open Payoff Visualization Notebook in Colab](https://colab.research.google.com/drive/13xwLl9doOD8MEC0W5DgH4s0hn6AR4CM_?usp=sharing)

## Note

本專案包含台指選擇權五週模擬交易分析，以及使用 Python 繪製選擇權策略損益圖的教學 notebook。

GitHub 可能會顯示 Invalid Notebook，無法直接預覽。  
若 notebook 無法正常顯示，請點擊上方的「Open Payoff Visualization Notebook in Colab」連結，直接在 Google Colab 中查看與執行。

## Project Structure

### 1. 專案背景與問題定義

本專案以台指選擇權為標的，進行五週模擬交易與策略分析。

根據每週市場情勢、總體經濟事件、波動率變化與籌碼面資訊，設計不同選擇權策略，並檢討其風險報酬表現。

分析重點包括權利金、履約價、損益兩平點、最大風險、部位規模與策略損益來源。

### 2. 市場情勢與策略判斷

每週整理市場背景與交易假設，作為策略選擇依據。

觀察指標包含：

- 國際政經事件
- 原油價格與通膨預期
- VIX 波動率指數
- P/C Ratio
- 外資期貨未平倉部位
- 三大法人籌碼變化
- 台股技術支撐與壓力區間

### 3. 選擇權策略設計

依據不同市場情境建立選擇權組合策略。

涵蓋策略包括：

- Iron Condor
- Bull Put Spread
- Long Straddle
- Short Strangle
- Call / Put Spread
- 多腿選擇權組合策略

針對各策略計算淨權利金、最大獲利、最大損失、損益兩平點與風險暴露。

### 4. 模擬交易績效分析

追蹤五週模擬交易結果，並以相同履約價進行平倉損益計算。

分析內容包含：

- 每週策略損益
- 累積損益
- 部位規模
- 權利金變化
- 策略實際表現與原先預期的落差

五週模擬交易最終累積損益為 **+344,100 元**。

### 5. 策略檢討與風險分析

針對每週策略結果進行事後檢討，分析策略成功或失敗的原因。

討論重點包含：

- 隱含波動率收斂
- 時間價值流失
- 履約價區間設定
- 事件風險
- 單邊行情突破風險
- 部位規模與保證金壓力
- 風險報酬比與最大損失控管

### 6. Python 損益圖視覺化教學

另外製作 Python notebook，示範如何繪製台指選擇權策略損益圖。

使用工具包含：

- Python
- NumPy
- Pandas
- Plotly

Notebook 內容包含基本買權與賣權損益計算、策略組合、損益兩平點標示，以及不同標的價格情境下的損益圖視覺化。

此 notebook 作為本專案的附加教學材料，用於說明選擇權策略損益結構與視覺化方法。
