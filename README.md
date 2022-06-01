# gfwlist 根据个人习惯进行了修改

## 使用说明

GFWList 地址(Github):
[https://raw.githubusercontent.com/zhaochangwu/gfwlist/master/gfwlist.txt](https://raw.githubusercontent.com/zhaochangwu/gfwlist/master/gfwlist.txt)

## 脚本说明

### 操作系统

**macOS 11.2 (20D64)**

### 脚本说明：

```shell
# 解码
base64 -d gfwlist.txt -o gfwlist_decode.txt
# 编码
base64 -i gfwlist_decode.txt -b 64 -o gfwlist.txt
```

### 改动记录
#### 2022年5月
- 新增`||steampowered.com`
- 删除`.steamcommunity.com`
- 删除`|http://store.steampowered.com/app/333600`

#### 2022年3月
- 新增`||rutracker.org`

#### 2021年7月
- 优化`||cloudfront.net`相关
- 新增`||adorama.com`
- 新增`||adsymptotic.com`
- 新增`||zoominfo.com`

#### 2021年6月
- 新增`||cloudflare.com`

#### 2021年5月

- 新增`||rustylake.com`
- 新增`||pramp.com`
- 新增`||njhzmxx.com`

#### 2021年3月

- 新增 `||dartlang.org`
- 新增 `||rvm_io.global.ssl.fastly.net`
- 删除 `@@||redirector.gvt1.com`
- 新增 `||jianli2017.top`
- 新增 `||developer.apple.com/cn/`
- 新增 `||sunnyxx.com`

#### 2021年2月

- 新增 `||logcg.com`
- 新增 `||kxcdn.com`
- 新增 `||printfriendly.com`
- 新增 `||tunnelblick.net`
- 新增 `||stackoverflow.com`
- 新增 `||youneed.win`
- 新增 `||flutter.dev`
- 新增 `||flutter-io.cn`
- 新增 `||dart.dev`
- 新增 `||rubygems.org`
- 新增 `||doubleclick.net`
- 新增 `||rubocop.org`
- 新增 `||ruby-lang.org`
- 新增 `||huacnlee.com`
- 新增 `||dartpad.dev`
- 新增 `||cnswift.org`
- 新增 `||google.cn`
- 新增 `||github.com`
- 修改 `.google.com` 为 `||google.com`
- 修改 `@@||fonts.googleapis.com` 为 `||fonts.googleapis.com`
- 移除 `@@|https://cdn.ampproject.org`

---

<a href="http://info.flagcounter.com/T2RV"><img src="http://s09.flagcounter.com/count2/T2RV/bg_FFFFFF/txt_000000/border_CCCCCC/columns_6/maxflags_20/viewers_GFWList/labels_1/pageviews_1/flags_0/percent_0/" border="0"></a>

|[Annoucements & Discussions][chat-room]|
|:---:|
| [![chat-metadata]][chat-room]|

[chat-metadata]: https://img.shields.io/gitter/room/nwjs/nw.js.svg?style=flat-square "Join the chat"
[chat-room]: https://gitter.im/gfwlist/gfwlist?utm_source=share-link&utm_medium=link&utm_campaign=share-link "GFWList@Gitter"

:tulip:***For the tiny version of GFWList, please visit [tinylist project homepage](https://github.com/gfwlist/tinylist).***
******

:hammer:***For source code stemmed from premier GFWList which is now being used for maintenance, please visit [apollyon project](https://github.com/gfwlist/apollyon).***
******

# gfwlist
## The OFFICIAL gfwlist here!

Everyone knows that netizens in Mainland China are under oppression. There is a government-run firewall that blocks and interferes with websites containing sensitive or unwanted information. Meanwhile there’s an extensive network of self-censors in all domestic Internet companies who delete contents which might incur the wrath of the people behind the rigorous censorship regime, while there are also lots of websites refuse to crouch. Hence they are often blocked.

There are other cases for example many streaming services or restricted content providers have blocked IPs from China. What a pity!

We don't dismantle the wall, we just find a hole to bypass then instead. Don't ask us how to bypass, we don't know. And don't ask us what a wall is, it's not a continuous vertical brick or stone structure that encloses or divides an area of land.

TL;DR: This list embraces websites which Chinese authorities and some service providers don't want Chinese to view on the Internet.

---
## If you want to report, make sure check our [wiki](https://github.com/gfwlist/gfwlist/wiki/Cautions) first.

## In case you want to request anonymity, you can send report to us directly, please visit [this profile](https://github.com/cicku) to retrieve the email address.

WARNING:

* We **WON'T** deal with reports from users of provinces below:

  - Tibet (Tibet Autonomous Region)
  - Shinjang (XinJiang Uyghur Autonomous Region)
  - Qinghai (Qinghai Province)

* GFWList doesn't provide prompt update for URLs submitted, normally they will be fully tested before adding into the list.

---

GFWList URL(Github): https://raw.githubusercontent.com/gfwlist/gfwlist/master/gfwlist.txt

**Notwithstanding Github is competent for distribution, to hedge outages or connection issues we still recommend using any URL below.**

**Official mirror URLs:**
1. Pagure: https://pagure.io/gfwlist/raw/master/f/gfwlist.txt

2. Repo.or.cz: http://repo.or.cz/gfwlist.git/blob_plain/HEAD:/gfwlist.txt

3. Bitbucket: https://bitbucket.org/gfwlist/gfwlist/raw/HEAD/gfwlist.txt

4. Gitlab: https://gitlab.com/gfwlist/gfwlist/raw/master/gfwlist.txt

5. TuxFamily: https://git.tuxfamily.org/gfwlist/gfwlist.git/plain/gfwlist.txt

**Mirrors can alleviate the problem caused by raw file fetch at GitHub which might be a breach of [GitHub ToS](https://github.com/site/terms).**
