# 比特彗星-客户端过滤规则

## 关于

本仓库用于存储适用于比特彗星的客户端过滤规则  
以便于客户端通过此链接自动更新过滤列表  

此功能在比特彗星2.15版本中被引入 用于取代过去高级设置中的旧选项  
* `bittorrent.anti_leech_banned_client_names`
* `bittorrent.anti_leech_banned_peer_ids`
* `bittorrent.anti_leech_banned_ports`

## 链接

* 官方使用教程：[链接](https://wiki.bitcomet.com/bitcomet_options#client_filter)  
* 查看过滤列表：[链接](./Client_Filter.json)  
* 订阅用链接(GitHub)：[链接](https://raw.githubusercontent.com/bitcomet-post-bar/BC-Client-Filter/refs/heads/main/Client_Filter.json)  
* 订阅用链接(Gitee)：[链接](https://gitee.com/bitcomet-post-bar/BC-Client-Filter/raw/main/Client_Filter.json)  

---

## 已经屏蔽的客户端

| 序 号 | 规 则 类 型 | 规 则 值 | 动 作 | 备 注 |
|--- | --- | --- | --- | ---|
| 0 | 客户端名称 | trafficconsume | 禁止 | 恶意刷流程序 |
| 1 | PeerID 前缀 | -HP??? | 禁止 | 恶意刷流程序 |
| 2 | PeerID 前缀 | -XM??? | 禁止 | 恶意刷流程序 |
| 3 | PeerID 前缀 | -DT??? | 禁止 | 恶意刷流程序 |
| 4 | 客户端名称 | Gopeed dev | 禁止 | 被恶意改造的正常客户端 |
| 5 | 客户端名称 | rain 0.0.0 | 禁止 | 被恶意改造的正常客户端 |
| 6 | 客户端名称 | taipei-torrent | 禁止 | 被恶意改造的正常客户端-过时客户端 |
| 7 | Peer 监听端口 | 15001 | 禁止 | 迅雷吸血特征-端口 |
| 8 | Peer 监听端口 | 15000 | 禁止 | 迅雷吸血特征-端口 |
| 9 | PeerID 前缀 | -XL0018 | 禁止 | 迅雷吸血特征-peeID |
| 10 | 客户端名称 | xfplay | 禁止 | 磁力播放器-影音先锋 |
| 11 | 客户端名称 | StellarPlayer | 禁止 | 磁力播放器-恒星播放器 |
| 12 | 客户端名称 | dandanplay | 禁止 | 磁力播放器-弹弹PLAY |
| 13 | 默认规则 | 任何 | 允许 | 默认规则 |

---

## 参考
* [吸血客户端收集与解决方法](https://www.cometbbs.com/t/%E5%90%B8%E8%A1%80%E5%AE%A2%E6%88%B7%E7%AB%AF%E6%94%B6%E9%9B%86%E4%B8%8E%E8%A7%A3%E5%86%B3%E6%96%B9%E6%B3%95/92122)
* [PeerBanHelper](https://github.com/PBH-BTN/PeerBanHelper)