## 原 ChinaList 停止維護，此專案僅供本人使用。

雖然應該沒人會看到這邊了，還是想感謝曾參與過的朋友，特別是 [Gythialy](https://github.com/gythialy)，四年多來向他學了不少東西，十分受用！當初僅憑著一股熱血加入，很多東西不懂，一直都是他從旁協助，還開發了許多工具幫助專案進行，直到停止維護前都沒少操過心，若少了這位朋友應該撐不了這麼久。

我很討厭廣告，可以說根本就沒喜歡過，若能為同樣受廣告轟炸之苦的人們盡一份力，犧牲一小部份時間，又有何不可？但隨著時間推移，熱情終究會消耗殆盡，剩下的就只有一份義務撐著。ABP 推出非侵入式廣告設定之前，就看過有人在論壇說一些「廣告怎麼又出現啦」「是不是收了那些網站的錢啊」之類的話，但還算是極少數。在官方推出這該死的東西之後，這類言論就愈來越多了，跑到 Google Code 專案上面亂罵的也不是沒有，但解釋了又怎麼樣呢？官方控制的白名單都是公開的，剛開始也就寥寥幾個英文網站列在上面，中文網站根本不會受到影響，但看不懂或懶得看的人就又開始造謠了。每當看到這些言論只覺得非常無力，就連 ChinaList 裡頭的白名單也跟著中槍。ChinaList 的條件集絕大多數都是靠用戶回報修改的，剩下的就靠平常上網發現漏擋或誤擋等問題後進行更新。

加入白名單的用意是確保網站能正常運作，如果白名單開的範圍太大還盡量限制類型或網域來減少出現不必要的廣告，只不過對某些人而言 "@@" 和 "@#@" 就是收錢的象徵。真可惜，我們一毛錢也沒拿過。

前陣子和 [Gythialy](https://github.com/gythialy) 都有自己的事情要忙 (他又比我更忙)，再加上人肉篩選官方 issue reporter 上大量的誤報及無用資訊又得花上一堆時間，處理速度確實不像原本那麼快。但至少都能在一到兩天內處理完畢。
想起以前 Google Code 上面有時出現新 issue 後幾分鐘，甚至一小時內就可以處理完，那還真是一段十分有閒的時光啊。

總之，人力不足再加上近年來難搞的網站越來越多，許多光靠 ABP 根本就無法解決的問題似乎讓大家對 ChinList 大失所望。官方大概也認為我們在扯後腿，反正在收到官方寄來說要撤換 ChinaList 之後一切都無所謂了。

- 官方宣布 3/21 撤換預設的中文列表，我前一天才收到信？無所謂。
- [官方部落格](https://adblockplus.org/blog/switching-default-blocking-lists-for-chinese-users)鬼話連篇？無所謂。
- 覺得 "blocking video ads will be much better." 是因為原本規則寫不好的關係？無所謂。
- 直接在表頭加入 !redirect 這種東西直接強迫現有用戶改為訂閱新列表？無恥，但無所謂。

既然官方覺得 "paying the list maintainers allowed us to find people fast and, above all, ensure flexibility and quality." 我也沒話說，難怪信裡面還問我要不要加入，還強調是「有給薪」的，原來是以為我們因為沒錢拿所以效率低落，無所謂。

最後的 "...provide our users in the Chinese-speaking community with an adblocking experience worthy of the name Adblock Plus." 看完之後吐了滿桌的血，反正在官方眼裡我們就是愧對 ABP 名號吧。

相關連結

* [https://github.com/chinalist/chinalist/wiki](https://github.com/chinalist/chinalist/wiki)
* [https://www.firefox.net.cn/read-48998-1](https://www.firefox.net.cn/read-48998-1)

## 从此，广告已成往事

专为所有中文用户(简/繁)维护的 Adblock Plus 过滤列表

## 从今日(2014/03/26)起, 本项目停止维护，[原因见此](https://github.com/chinalist/chinalist/wiki)。

## 公告

由于 [ABP 策略调整](https://adblockplus.org/blog/switching-default-blocking-lists-for-chinese-users)，ChinaList 将作为独立的民间项目，与 ABP 官方不再有任何关系(2014-3-24 起)。

项目做如下调整，下阶段目标，参见[路线图](https://github.com/chinalist/chinalist/wiki/Roadmap)

- 原 ChinaList Lazy 改为 ChinaList，将作为以后本项目维护的主列表，不依赖任何第三方列表
- 原 ChinaList 改为 ChinaList Lite, 和原策略保持一致，作为 EasyList 的补充列表

注：单独订阅 ChinaList Lazy，ChinaList 用户不受任何影响，列表会自动重定向。订阅官方 EasyList + ChinaList 用户，如果想使用我们维护的列表需要手动更改订阅。如不更改会自动更新到 ABP 官方 fork 的我们的项目列表。

## 补充

Adblock Plus非万能，其实现原理[在此](http://adblockplus.org/zh_CN/faq_internal#policies)。其无法完成之任务，推荐使用脚本来协助完成。

#### 已有站点列表

##### [Greasemonkey](https://addons.mozilla.org/zh-cn/firefox/addon/greasemonkey/) 0.9.8+ / [Scriptish](https://addons.mozilla.org/zh-cn/firefox/addon/scriptish/) 

- [调整远景论坛](https://raw.github.com/chinalist/chinalist/master/scripts/remove_ads_for_pcbeta.user.js)
- [Disable anti ABP for hkgolden.com](https://raw.github.com/chinalist/chinalist/master/scripts/disable_hkgolden_com.user.js)
- [隐藏华军验证码广告](http://userscripts.org/scripts/show/129215)
- [去各大视频网站黑屏](http://userscripts.org/scripts/show/119622)

##### 其他 

- [人人网改造器](http://userscripts.org/scripts/show/45836)
- [去各大视频网站黑屏](https://code.google.com/p/haoutil/)  

## LICENSE 

- ChinaList [Creative Commons 3.0 BY-SA](http://creativecommons.org/licenses/by-sa/3.0/)
- ChinaList Lite [Artistic License 2.0](https://github.com/chinalist/chinalist/blob/master/LICENSE)
- ChinaList Privacy [Artistic License 2.0](https://github.com/chinalist/chinalist/blob/master/LICENSE)
- ChinaList Anti Social [Artistic License 2.0](https://github.com/chinalist/chinalist/blob/master/LICENSE)

-------------

欢迎参与[讨论组](https://groups.google.com/group/adblock-chinalist)(Maybe GFWed)]，发表您的意见丶建议或提交 [Issues](https://github.com/chinalist/chinalist/issues)。

如果您对 Adblock Plus 和 ChinaList 感兴趣，请查阅[官方文档](http://adblockplus.org/zh_CN/documentation)或者项目 [Wiki](https://github.com/chinalist/chinalist/wiki/) 中的文档，也许对您有帮助。

*Need help!*  
欢迎加入 ChinaList 团队，加入前请先查看[技能需求](https://github.com/chinalist/chinalist/wiki/The_skills_needed_to_join_ChinaList)，看自己是否满足条件 
