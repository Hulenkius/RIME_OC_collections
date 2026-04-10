# 臤徘斯上古三拼方案

> 十年前本人開始日常使用中古三拼輸入法打字，在打字過程中即熟悉了切韻音系；本項目旨在設計一款上古三拼輸入法，以便在日常使用中學習上古漢語音系。

受 [上游倉庫](https://github.com/Hulenkius/RIME_OC_collections) 和 [polyhedron 中古三拼](https://github.com/biopolyhedron/rime-middle-chinese) 啓發，使用 [由知乎 Nulll 老師整理的上古漢語擬音](https://zhuanlan.zhihu.com/p/12987993957)（新最小上古漢語）字表，本人設計了三拼輸入法方案，旨在實現在日常打字中學習上古漢語。

爲了滿足日常使用要求，補充了《通用规范汉字表》中的漢字`（當前進度1945/2415）`。其中，標❗️的字不見於《字表》而見於《廣韻》，其字音由中古音及聲符推出；標‼️的字不見於《廣韻》，其字音由現代各方言反推而得；❗️或‼️之後若有字，則表示此條字音參考此字推出。

> 僅爲當代打字方便而添加，不代表上古漢語眞存在這些字，且如此發音！個人手工編輯，可能有錯漏！

三拼鍵位如下圖所示，設計思路與polyhedron中古三拼類似，以便慣用中古三拼者快速適應：

<img width="592" height="750" alt="image" src="https://github.com/user-attachments/assets/d326e954-7d39-4d15-a25b-8ed2bf82fa77" />

例：
| 字 | 音 | 碼 |
|:-|:-|:-|
| 上 | daŋʔ > `d a ŋʔ` | `d q w` |
| 位 | wrəps > `w rə ps` | `u t m` |
| 的 | tˤewk > `t ˤe wk` | `t d o` |
| 漢 | n̥ˤar > `n̥ ˤa r` | `N a g` 或 `nb a g` |
| 臨 | C.rum > `r ru m` | `r n d` |

> 以下爲上游倉庫 README。

# RIME_OC_collections

![Title](https://user-images.githubusercontent.com/32562298/213803086-ee90a096-9f5f-4ba2-8ed9-7db4f2188549.jpg)

本項目用於分享一些上古漢語擬音的 RIME 輸入方案。**更多的時候是作爲一個臨時反查上古音的工具。**

本倉庫收錄於 [中州韻輸入法非普通話漢語拼音方案全集](https://github.com/laubonghaudoi/Chinese_Rime)。

**在線體驗本項目：[遠見齋輸入法在線試用平臺](https://rime.vistudium.top/)**
- 進入 `RPPI` 添加方案
- 找到 `漢語` - `古音` - `上古音方案集`
- 推薦再裝一個 `漢語` - `字形` - `倉頡五代` 用於反查
- 安裝並部署

目前已製作下列方案：

- [知乎新派（Nulll 表格）](nulll.md)
- [msoeg 擬音（含《廣韻形聲考》）](msoeg.md)
- [白一平-沙加爾擬音](baxter-sagart.md)
- [許思萊擬音](shuessler.md)
- [斯塔羅斯金擬音（晚期上古、詩經韻尾）](starostin.md)
- [鄭張尚芳擬音](zhengzhang.md)
- [白一平 1992 版擬音](baxter1992.md)
- [金理新擬音](jinlixin.md)
- [王力擬音](wangli.md)
- [李方桂擬音](lifanggui.md)
- [周法高擬音](zhoufagao.md)

點擊對應連結可查看相應的方案介紹、轉寫說明。

在網頁電腦端撳「Code」按鈕，選擇「[Download ZIP](https://codeload.github.com/Hulenkius/RIME_OC_collections/zip/refs/heads/main)」即可打包下載到本地。

你也可以使用其他 git 下載方式，或使用 plum 進行本地安裝。
