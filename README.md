# 中州韻粵語拼音輸入法分歧拼音系統補丁
* 依賴於：[`rime/rime-cantonese`](https://github.com/rime/rime-cantonese)
* 呢個補丁將`jyut6ping3*.dict.yaml`嘅詞句轉換成其他主流拼音系統，方便唔係用開「粵拼」嘅人用RIME，同埋學習用「粵拼」轉寫。
* **長遠請考慮轉用香港語言學學會嘅粵語拼音方案（「粵拼」），一嚟科學，二嚟貼近國際音標，三嚟大部分嘅現代粵語資源都係用「粵拼」標音。如果閣下希望同本地粵語文化接軌，請轉用粵拼。**
* 呢度嘅程式碼係都以補丁方式實現，唔會影響其他輸入法檔案。

## 我用緊邊種拼音系統？
拼音系統  | 「翠」| 「獎」 | 「完」 | 「花」 | 常見於（純粹主觀感覺）
 :-------------: | :-------------: | :--------: | :---: |:----: | -----
 [國際音標](https://zh.wikipedia.org/wiki/%E5%9C%8B%E9%9A%9B%E9%9F%B3%E6%A8%99) | t͡sʰɵy | t͡sœːŋ | jyːn | faː | 語言學研究
 [**粵拼**](https://zh.wikipedia.org/zh-hk/%E9%A6%99%E6%B8%AF%E8%AA%9E%E8%A8%80%E5%AD%B8%E5%AD%B8%E6%9C%83%E7%B2%B5%E8%AA%9E%E6%8B%BC%E9%9F%B3%E6%96%B9%E6%A1%88) | **ceoi** | **zoeng** | **jyun**| **faa** |**現代學術資料，社羣粵語資料，字典**
[耶魯拼音](https://zh.wikipedia.org/wiki/%E8%80%B6%E9%AD%AF%E6%8B%BC%E9%9F%B3#%E7%B2%A4%E8%AF%AD%E8%80%B6%E9%B2%81%E6%8B%BC%E9%9F%B3)|  cheui | jeung | yun | fa| 上世紀學術資料，Gboard等輸入法
[教院式拼音](https://zh.wikipedia.org/wiki/%E6%95%99%E8%82%B2%E5%AD%B8%E9%99%A2%E6%8B%BC%E9%9F%B3%E6%96%B9%E6%A1%88) | tsoey | dzoeng | jyn | faa| 香港教育局教材
[劉錫祥拼音](https://zh.wikipedia.org/wiki/%E5%8A%89%E9%8C%AB%E7%A5%A5%E6%8B%BC%E9%9F%B3)| chui| jeung| yuen | fa| 外國嘅粵語轉寫，「網上廣東話輸入法」，面向外國人嘅粵語教材
[黃錫凌拼音](https://zh.wikipedia.org/wiki/%E9%BB%83%E9%8C%AB%E5%87%8C%E7%BE%85%E9%A6%AC%E6%8B%BC%E9%9F%B3)|tseue|dzeung|yuen|faa|《粵音韻彙》

## 點解我要學粵拼？

(待擴充)

如果睇完以上嘅簡介，閣下已經決定咗要學習「粵拼」，但係覺得無從入手，噉喺[呢度](INSTRUCTIONS.md#安裝方法)我提供咗幾個過渡方案，俾閣下用住熟悉嘅拼音嚟用RIME先。選字表上面會顯示正確嘅粵拼，方便大家對照讀音。

當你對自己嘅粵拼有信心嘅時候，就可以參考[呢度](INSTRUCTIONS.md#解安裝方法)嘅方法，將補丁移除，體驗中州韻輸入法嘅完整功能。

## 授權條款
GNU較寬鬆公共授權條款（第三版）。詳細條款請參閱[LICENSE](LICENSE)。
