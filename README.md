tools
=====

Save The Web Project 所使用的工具列表

网站故障排除
------------

### 连接测试

| 工具名                                         | 简介                              |
| ---------------------------------------------- | --------------------------------- |
| [Online nslookup](https://www.nslookup.io/)    | 在线 DNS 检测                     |
| [Ping.PE](https://ping.pe/)                    | 全球 Ping 检测                    |
| [网站测速工具 boce.com](https://www.boce.com/) | 内地 wegt 检测                    |
| [网站测速 17CE.COM](https://www.17ce.com/)     | 内地 + 部分常见海外地区 wegt 检测 |
| [证书检测 myssl.com](https://myssl.com/)       | 亚信提供的 SSL/TLS 证书检测       |

### RSS 订阅

| 工具名                               | 简介                           |
| ------------------------------------ | ------------------------------ |
| [W3C Feed Validation Service][W3C_F] | 测试 RSS 订阅是否符合 W3C 标准 |

[W3C_F]: https://validator.w3.org/feed/

### 域名

| 工具名                                       | 简介                                 |
| -------------------------------------------- | ------------------------------------ |
| [ICANN Lookup](https://lookup.icann.org/)    | 查询 Whois 的网站，由 ICANN 官方运营 |
| [Telegram@Whois_Bot](https://t.me/Whois_Bot) | 查询 Whois 的 Telegram 机器人        |

> 注意：部分域名注册商有防抢注的保护措施，会使whois的显示出来的到期时间看起来延后一年，但是实际上这个域名已被释放。注意甄别顶级域名解析到的ip是否属于whois中查询到的服务商所有，或直接在注册商处查询whois，以判定域名是否处于防抢注状态。

快照 & 缓存 & 存档
------------------

| 工具名                                      | 简介                                                         |
| ------------------------------------------- | ------------------------------------------------------------ |
| [Wayback Machine](https://web.archive.org/) | 自动保存容易被抓取的网页，可以看到网站之前的面貌             |
| [Archive.today](https://archive.ph/)[^AT]   | 不会自动抓取网页，需要手动保存                               |
| [Archivarix](https://archivarix.com/)       | 基于 Wayback Machine 的数据恢复网站的工具，200个文件以下免费 |
| [Wayback Machine Downloader][WMD]           | 基于 Ruby 从 Wayback Machine 下载网站内容的开源工具          |
| [dessant/web-archives][dwa]                 | 快速检查网页快照的浏览器扩展                                 |
| [wabarc/wayback][w-w]                       | 功能强大的工具包，详细介绍需查看脚注[^w-w]                   |
| [elsiehupp/wikiteam3][wiki3]                | wikiteam 用于备份 mediawiki 的工具包（这是python3版本）     |

[^AT]:
    AT 的域名多变，如果无法访问常用的 `archive.is`，则可以访问 `Archive.today` 自动跳转到可能能够使用的域名。

    以下是 Archive.today 曾使用过的域名：

    +   `archive.is`
    +   `archive.ph`
    +   `archive.vn`
    +   `archive.fo`

    如果 IP 被 AT 封锁了，则可以使用洋葱域名： `http://archiveiya74codqgiixo33q62qlrqtkgmcitqx5u2oeqnmn5bpcbiyd.onion/` 在 Tor 访问。

[WMD]: https://github.com/hartator/wayback-machine-downloader

[dwa]: https://github.com/dessant/web-archives

[w-w]: https://github.com/wabarc/wayback

[^w-w]: 这是快照网页的工具包，可以快速的批量保存网页，全平台支持，如果想要简单使用，那么可以在 Telegram 私聊 @wabarc_bot 这个机器人。

[wiki3]: https://github.com/elsiehupp/wikiteam3

WordPress插件
-------------

| 工具名                                      | 简介                                                                                    |
| ------------------------------------------- | --------------------------------------------------------------------------------------- |
| [Archivarix External Images Importer][AEII] | 自动从 archive.org 下载现无法访问的图片外链，并本地化                                   |
| [IMGspider][IMGs]                           | 下载图片外链，并本地化(该插件有BUG，会出现重复下载、已本地化的外链重新“变回”外链的情况) |

[AEII]: https://wordpress.org/plugins/archivarix-external-images-importer/

[IMGs]: https://wordpress.org/plugins/imgspider/

其他工具
--------

| 工具名                                              | 简介                       |
| --------------------------------------------------- | -------------------------- |
| [Open Multiple URLs / Bulk Link Opener][OM_URL]     | 一键打开多个链接           |
| [URL Encode / URL Decode - Savant Tools][URC_ED]    | 编码与解码 URL 的转义字符  |
| [HTML Encode / HTML Decode - Savant Tools][HTML_ED] | 编码与解码 HTML 的转义字符 |

[OM_URL]: https://savanttools.com/open-multiple-urls

[URC_ED]: https://savanttools.com/url-decode

[HTML_ED]: https://savanttools.com/html-encode
