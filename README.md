# 艦隊收藏中文化
艦隊收藏介面中文化\
Traditional Chinese Patch for Kancolle.\
透過KCCProxy運作，可搭配poi、74式電子觀測儀、或單純瀏覽器運作，原理類似魔改。\
翻譯進度更新至2021/08/20夏活。\
![Title](https://i.imgur.com/mUIReZV.jpg)

## 使用方法
請到Wiki查看[詳細安裝教學](https://github.com/ivon852/KanColle-Traditional-Chinese-Patch/wiki)。

## 致謝
此模組是基於[InochiPM的KanColle-English-Patch-KCCP](https://github.com/InochiPM/KanColle-English-Patch-KCCP)專案製作，部分中文翻譯來自kc3和艦娘百科。\
原始致謝列表可至該頁面查看。

## 開發相關
每週會跟英文版確認進度並更新翻譯，有任何建議歡迎發Issue。\
可切換至dev分支下載含有psd檔的壓縮包進行修改。

#### 使用到的字體
除了dev分支的psd檔案外，這個專案還使用了以下字體，需自行安裝:
- A-OTF リュウミン Pr6n (R為基礎，粗體一般M就夠)
- A-OTF ゴシックMB101 Pr6N (EB-KL為主，最多加上仿粗體)

#### 未翻譯的部分
- 裝備名稱圖卡 (位於kcs2/resources/slots/)
- 艦娘名稱文本 (位於kcs2/js/main.js/ignore-raw_text_translations/ignore-_ships.json)
- 裝備名稱文本 (位於kcs2/js/main.js/ignore-raw_text_translations/ignore-_equips.json)

#### 待修正列表
- kcs2\img\battle\battle_telop\txt_start.png 參照原本的noise
- world的字體加寬
- skin3的UI對齊
- 任務返回的按鈕對齊