# rime-cantonese_auxcode
使用倉頡/速成/標準兩分/改版兩分對RIME粵拼方案的外掛axu_code的lua的簡易部署方案。 Simple Deployment Guide for axu_code Lua Plugin with Cangjie/Sukeng/Standard Two-Part/Revised Two-Part Input Methods for RIME Cantonese Pinyin Scheme  cantonese / 廣東話 / 廣東話 / 粵語 / 粤语 / 粵拼 / 粤拼

## 0.簡述

本項目為膠水整合方案。為[Rime輸入法輔助碼與音形分離插件](https://github.com/HowcanoeWang/rime-lua-aux-code)添加一項支持[Rime 粵語拼音方案](https://github.com/rime/rime-cantonese)的簡易部署方案。

使用本方案將為Rime粵拼方案添加支持使用 倉頡/速成/標準兩分/改版兩分 等輔助碼進行更有效篩選單字/組詞
## 2.使用

- 依想使用的輔助碼下載，按照路徑部署至`用戶文件夾`，”重新部署“ 即可
  - 右鍵於windons下的任務列RIME圖標，選擇`用戶文件夾`打開
  - jyut6ping3.custom.yaml 部署至 用戶文件夾\
  - aux_code.lua、leongfan_code.txt 等文檔 部署至 用戶文件夾\lua\ （如無該資料夾可自行創建命名即可）
  - 右鍵於windons下的任務列RIME圖標，選擇“重新部署”

## 3. 使用圖
<p align="center">
<img src="https://github.com/yuOpghH/rime-cantonese_auxcode/blob/main/%E6%87%89%E7%94%A8%E5%9C%96/test1.png"/>
<img src="https://github.com/yuOpghH/rime-cantonese_auxcode/blob/main/%E6%87%89%E7%94%A8%E5%9C%96/test2.png"/>
</p>

----

 - 組詞亦可篩選，但僅限尾字
 - 修改觸發鍵及自定義輔助碼方案等等問題，請參考原方案問答 [Rime輸入法輔助碼與音形分離插件](https://github.com/HowcanoeWang/rime-lua-aux-code)
 - 兩分是何物？例：蒜 = 艹 (cou2) + 示 (si6) `蒜 = s + yun + ;（觸發鍵） + c (艹cou2) + s(示si6) = syun;cs` 。參考[字海網首頁：兩分部首拆解查詢](http://www.yedict.com/)
 - 關於改版兩分輔助碼的鍵位表，參考 [新定兩分碼表](https://github.com/yuOpghH/rime-jyutsp-loengfan)

## 4. 致謝
- 感謝以下項目的無私貢獻及項目成果。可能有遺漏敬請原諒。
  - 外掛程式來源 [Rime輸入法輔助碼與音形分離插件](https://github.com/HowcanoeWang/rime-lua-aux-code)
  - 粵拼方案來源 [Rime 粵語拼音方案](https://github.com/rime/rime-cantonese)
  - 粵語兩分來源 [粵語兩分](https://github.com/CanCLID/rime-loengfan)
## 5. 感興趣

##### 感興趣的話歡迎瀏覽其他方案版本：


| 粵語雙拼方案 | 學習成本 | 揀字率 | 連續雙碼長句輸出 | 一鍵快碼 | 輔助碼篩選字詞 | 字詞固頂 | 簡拼輸出長詞
| :------- | ------: | -------: |  -------: |  -------: |  -------: |  -------: |  -------: | 
| [jyutsp-real <br>粵語雙拼<br>純雙拼](https://github.com/yuOpghH/rime-jyutsp-real)  | 低。僅需記憶鍵位映射 | 大量重複音節 | ✓ | ✓ |  |  | 
| [jyutsp-loengfan<br>粵語雙拼<br>兩分輔助碼](https://github.com/yuOpghH/rime-jyutsp-loengfan)   | 較低。幾乎可見可拆 | 能初步篩選同部首 | ✓ | ✓ | ✓ |  | 
| [jyutsp-goi<br>粵語雙拼<br>倉頡輔助碼](https://github.com/yuOpghH/rime-jyutsp-goi)  | 較高。120個倉頡字根 | 三千字內5.8% | ✓ | ✓ | ✓ | ✓ | ✓ |

