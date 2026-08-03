\# 中文學習遊戲 — 專案規則



\## 檔案結構

\- 只可以有兩個檔案:index.html 同 vocabulary-data.json

\- index.html 就係成個遊戲(字詞資料 inline 喺 script 入面);檔名唔可以改,GitHub Pages 靠佢做入口

\- vocabulary-data.json 係字詞嘅鏡像備份,遊戲唔會 fetch 佢;改字詞要兩邊一齊改

\- 唔好新增 README、guide、備份檔



\## 字詞標準(香港教育標準)

\- 一律繁體字、標準書面語

\- 唔可以用粵語口語詞入 vocabulary database

\- 例外:文化上必要嘅香港用語(如「嫲嫲」而非「奶奶」)

\- 每個 level 嘅字詞必須完全獨立,level 之間零重覆

\- K1 只用簡單象形字,難度按筆劃順序遞進至 F1



\## 遊戲設定

\- 雙 profile:Hugo 同 Sophie

\- 6 粒星掌握度,顯示喺 level 名旁邊

\- 唔要 knight / footman 之類 RPG 階級

\- 中文字要置中

\- 目標裝置:Samsung Galaxy(手機優先)



\## 改動方式

\- \*\*永遠唔好重寫成個檔案\*\*,只做針對性修改

\- 改完要保留用家已有進度資料

\- 改完用 node --check 驗證 JS syntax

