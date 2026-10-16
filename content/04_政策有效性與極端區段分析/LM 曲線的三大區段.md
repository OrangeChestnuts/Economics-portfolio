---
aliases:
  - 凱因斯區段
  - 中間區段
  - 古典區段
  - 極端區段
類型:
  - 定義
互動式圖表: true
狀態:
  - 已完成
up:
  - "[[🗂️ 總經-06 修正凱因斯模型（IS-LM）]]"
same:
  - "[[IS-LM 政策有效性分析與政策搭配]]"
down:
  - "[[流動性陷阱]]"
  - "[[古典極端]]"
建檔日: 2026-08-21
---

> [!summary]+ 概念前言 
> 根據大眾對「貨幣需求利率彈性 ($h$)」的敏感度不同，LM 曲線在不同利率水準下，會呈現出三種截然不同的斜率。這三大區段直接決定了政府在當下該使用財政政策還是貨幣政策，也是區分總體經濟學派的最強分水嶺。

---

# 一、 圖形解析：一條曲線，三個世界

<div style="background-color: var(--background-primary); border: 1px solid var(--background-modifier-border); border-radius: 8px; padding: 20px; max-width: 550px; margin: 20px auto;">
  <svg viewBox="0 0 500 400" width="100%" xmlns="http://www.w3.org/2000/svg">
    <!-- 箭頭定義區塊 -->
    <defs>
      <marker id="arrow" viewBox="0 0 10 10" refX="9" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse">
        <path d="M 0 0 L 10 5 L 0 10 z" fill="#888888" />
      </marker>
    </defs>

    <!-- 座標軸 -->
    <line x1="50" y1="350" x2="450" y2="350" stroke="#888888" stroke-width="2" marker-end="url(#arrow)"/>
    <line x1="50" y1="350" x2="50" y2="30" stroke="#888888" stroke-width="2" marker-end="url(#arrow)"/>
    <text x="420" y="380" font-family="sans-serif" font-size="14" fill="currentColor">Y (產出)</text>
    <text x="20" y="20" font-family="sans-serif" font-size="14" fill="currentColor">r (利率)</text>

    <!-- 凱因斯區段 (水平) -->
    <line x1="50" y1="300" x2="200" y2="300" stroke="#3b82f6" stroke-width="4" />
    <text x="70" y="285" font-family="sans-serif" font-size="15" fill="#3b82f6" font-weight="bold">凱因斯區段</text>
    <text x="70" y="325" font-family="sans-serif" font-size="13" fill="#3b82f6">h → ∞ (流動性陷阱)</text>

    <!-- 中間區段 (正斜率) -->
    <path d="M 200 300 C 280 300, 310 180, 350 100" fill="transparent" stroke="#8b5cf6" stroke-width="4" />
    <text x="200" y="190" font-family="sans-serif" font-size="15" fill="#8b5cf6" font-weight="bold">中間區段</text>
    <text x="200" y="215" font-family="sans-serif" font-size="13" fill="#8b5cf6">0 &lt; h &lt; ∞</text>

    <!-- 古典區段 (垂直) -->
    <line x1="350" y1="100" x2="350" y2="40" stroke="#ef4444" stroke-width="4" />
    <text x="365" y="80" font-family="sans-serif" font-size="15" fill="#ef4444" font-weight="bold">古典區段</text>
    <text x="365" y="105" font-family="sans-serif" font-size="13" fill="#ef4444">h = 0</text>
    
    <!-- 虛線分隔線 -->
    <line x1="200" y1="350" x2="200" y2="300" stroke="#888888" stroke-dasharray="4,4" stroke-width="1.5" />
    <line x1="350" y1="350" x2="350" y2="100" stroke="#888888" stroke-dasharray="4,4" stroke-width="1.5" />
    <text x="195" y="370" font-family="sans-serif" font-size="12" fill="#888888">Y₁</text>
    <text x="345" y="370" font-family="sans-serif" font-size="12" fill="#888888">Y₂</text>
  </svg>
</div>

---

# 二、 三大區段特性比較表

在解題時，請直接將圖形的「幾何特徵」對應到下表的「政策結論」：

| 區段名稱                 | 圖形長相    | 利率彈性 ($h$)              | 經濟學派   | 政策有效性結論                 | 核心原因                               |
| :------------------- | :------ | :---------------------- | :----- | :---------------------- | :--------------------------------- |
| **凱因斯區段<br>(流動性陷阱)** | **水平線** | $h \to \infty$<br>(無限大) | 凱因斯學派  | **財政政策最有效**<br>貨幣政策完全無效 | 利率已降至谷底，央行印再多錢都會被民眾以現金形式囤積，無法刺激投資。 |
| **中間區段<br>(常態區段)**   | **正斜率** | $0 < h < \infty$        | 新古典綜合派 | **兩者皆有效**<br>(端看斜率陡緩)   | 利率與所得處於正常波動範圍，符合一般常態經濟運作。          |
| **古典區段<br>(古典極端)**   | **垂直線** | $h = 0$<br>(完全無彈性)      | 古典學派   | **貨幣政策最有效**<br>財政政策完全無效 | 貨幣需求僅受所得影響。政府若擴張支出，會引發 100% 的排擠效應。 |

---
# 三、 考點深掘：極端彈性 $h \to \infty$ 的真實含義

在考卷上看到 $h \to \infty$（貨幣需求利率彈性趨近無限大）時，請不要單純用數學的「變動 1% 會造成多大影響」來解讀。這其實是一個**絕對的臨界點**，請直接聯想到凱因斯學派的 **「無底洞效應」**：

1. **經濟直覺 (無底洞效應)**：
   當市場利率跌到谷底（例如接近 0%），所有人都有強烈的預期心理：「利率不可能再低了，未來一定會升息」。因為**利率與債券價格呈反比**，升息代表未來債券價格必跌。既然買債券穩賠不賺，大眾對持有現金的偏好就變成了一個「黑洞」。
   
2. **對政策的致命打擊**：
   在這種極端狀態下，央行就算印再多鈔票放水，新增的貨幣也會瞬間被民眾「全部藏進床底或保險箱」囤積起來。因為大眾吸收資金的能力變成無限大，所以**無法迫使利率再往下降半步，貨幣政策宣告徹底死亡**（只能靠財政政策救經濟）。
   
3. **圖形意義 (完全彈性)**：
   在特定的極低利率水準下，大眾願意持有無限多的貨幣。因此 LM 曲線在這一段會變成一條**完全水平的直線**（斜率 $k/h = 0$）。

---
# 四、 微型 MOC：深度機制探討

這張統整表是應付「選擇題」與「比較題」的利器。若申論題要求你單獨解釋某個極端狀況的成因與推導，請直接進入以下兩張深度卡片：

* 為什麼在水平區段，印鈔票會完全沒用？
  👉 詳見深究筆記：[[流動性陷阱]]
* 為什麼在垂直區段，政府擴張支出會引發 100% 的排擠效應？
  👉 詳見深究筆記：[[古典極端]]