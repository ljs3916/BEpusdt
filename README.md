---
title: BEpusdt
emoji: 💳
colorFrom: green
colorTo: blue
sdk: docker
app_port: 8080
pinned: false
---
**鉂楋笍浣滆€呭０鏄庯細鏈」鐩负鐮旂┒瀛︿範鍖哄潡閾剧殑寮€婧愰」鐩紝涓嶆彁渚涗换浣曞舰寮忕殑鏀惰垂鏈嶅姟(璋ㄩ槻璇堥獥)
锛屼笉榧撳姳浠讳綍琛嶇敓閲戣瀺灞炴€х殑浜ゆ槗琛屼负锛屼笉璐熻矗浠讳綍浣跨敤鏈」鐩繘琛岀殑涓夋柟琛屼负锛涗娇鐢ㄨ繃绋嬩腑閬囪闂璇锋彁`issue`
鎴栫兢閲屼氦娴侊紝寮€婧愰」鐩鑷噸锛?*

---

# BEpusdt (Better Easy Payment USDT)

<p align="center">
<img src="./static/payment/assets/img/tether.svg" width="15%" alt="tether">
</p>
<p align="center">
<a href="https://www.gnu.org/licenses/gpl-3.0.html">
    <img src="https://img.shields.io/github/license/v03413/bepusdt" alt="license GPLV3">
</a>
<a href="https://github.com/v03413/bepusdt">
  <img src="https://img.shields.io/github/v/release/v03413/bepusdt" alt="GitHub Release">
</a>
<a href="https://github.com/v03413/bepusdt">
  <img src="https://img.shields.io/github/downloads/v03413/bepusdt/total" alt="GitHub Release">
</a>
<a href="https://hub.docker.com/r/v03413/bepusdt">
    <img src="https://img.shields.io/docker/pulls/v03413/bepusdt?style=flat-square&logo=docker" alt="Docker Pulls">
</a>
<a href="https://github.com/gin-gonic/gin">
    <img src="https://img.shields.io/github/stars/v03413/bepusdt?style=flat-square&logo=github" alt="GitHub Stars">
</a>
</p>

## 馃 浠嬬粛

缂樿捣浜巂Epusdt`锛屼絾涓嶄粎闄愪簬姝わ紝鍔犲叆浜嗕竴浜涙柊鐗规€э紝鑷村姏浜庢垚涓轰竴娆炬洿濂界敤鐨勪釜浜篳鍔犲瘑璐у竵`鏀舵缃戝叧銆?
## 馃帀 鏂扮壒鎬?
### 馃専 鐩墠鏀寔鏀舵缃戠粶

馃敟 涓绘祦缃戠粶锛歍RON Ethereum BSC Polygon<br>
鈿?鍏朵粬缃戠粶锛?X-Layer Solana Aptos Arbitrum-One Base [瀹屾暣鍒楄〃](./docs/trade-type.md)

- 鉁?瀹屽叏鍏煎 `Epusdt` 鎻掍欢鏃犵紳鏇挎崲
- 锔忊渽 鏀寔涓绘祦鍖哄潡缃戠粶 涓嶄粎闄愪簬`USDT`
- 鉁?鏀寔涓绘祦娉曞畾璐у竵 姹囩巼鑷姩鏇存柊
- 鉁?杞讳緷璧?鍗曚綋浜岃繘鍒舵枃浠?閮ㄧ讲渚挎嵎
- 鉁?鏀寔闈炶鍗曚氦鏄撶洃鎺?浣欓鍙樺姩閫氱煡
- 鉁?鏀寔鑷畾涔夋敮浠樼簿搴︿笌閫掑棰楃矑搴?- 鉁?搴曞眰鍖哄潡鎵弿 瀹夊叏纭 閫熷害绋冲畾
- 鉁?鏀寔娉㈠満鑳介噺浠ｇ悊 鍥炴敹瀹炴椂鐩戞帶
- 鉁?鍘熺敓鍏煎`鏄撴敮浠榒鏀跺崟 鎺ュ叆渚挎嵎
- 鉁?瀹屾暣鐙珛WEB鍚庡彴 鏂逛究閰嶇疆绠＄悊
- 鉁?鏀堕摱鍙版敮鎸佷腑鑻遍€傞厤 鍔╁姏鍑烘捣闇€姹?- 鉁?鍦板潃鐙崰妯″紡 搴曞眰鏀寔涓嶅畾棰濇敹娆?- 鉁?鏀寔MQTT娑堟伅鍙戝竷 浜ゆ槗淇℃伅鍗虫椂骞挎挱
- 鉁?蹇€熻凯浠ｆ湡 瓒呭瀹炵敤鐗规€у姛鑳界瓑浣犲彂鐜?
## 馃殌 蹇嵎鍚姩

Docker 蹇€熷惎鍔紝鎵ц瀹屽懡浠ゆ墦寮€鍦板潃`http://鏈嶅姟鍣↖P:8080`鍗冲彲鐪嬪埌鍒濆椤甸潰

```bash  
docker run -d --restart=unless-stopped -p 8080:8080 v03413/bepusdt:latest
```
## 馃搩 鎶€鏈枃妗? 

- 瀹夎锛歔Docker](docs/docker/docker.md) [Linux](docs/linux/install.md) [1Panel](./docs/1panel/README.md) [瀹濆](./docs/bt_panel/README.md)
- 寮€鍙戯細[API瀵规帴](docs/api/api.md) [璁㈠崟鍥炶皟](docs/notify/readme.md) [Python](https://github.com/luoyanglang/bepusdt-python-sdk) [PHP](https://github.com/v03413/bepusdt-php-sdk)
- 瀵规帴锛歔鐙Next](docs/api/dujiao-next/dujiao-next.md) [褰╄櫣鏄撴敮浠榏(https://github.com/v03413/Epay-BEpusdt) [whmcs](https://github.com/v03413/whmcs-gateway-epusdt) [EdgeKey](docs/api/edge-key/edge-key.md) [鍏跺畠](docs/api/other.md)
- 鍏跺畠锛歔https 閰嶇疆](./docs/ssl.md) [鏃堕挓鍚屾](docs/linux/systemd-timesyncd.md) [鏀堕摱鍙颁慨鏀筣(docs/payment-template/README.md)

## 馃柤 鍔熻兘鎴浘

| 鍓嶅彴鏀堕摱                                            | 鍚庡彴璁㈠崟                                             | Telegram 閫氱煡                                            |
|-------------------------------------------------|--------------------------------------------------|--------------------------------------------------------|
| <img src=./docs/images/1.png alt=鏀堕摱鍙?width=300> | <img src=./docs/images/2.png alt=鍚庡彴璁㈠崟 width=300> | <img src=./docs/images/3.png alt=Telegram閫氱煡 width=300> |

## 鉂?甯歌闂

- [鏈嶅姟鍣ㄩ厤缃€ц兘閫夊瀷鎺ㄨ崘 鈿★笍](./docs/faq/server.md)
- [鏈嶅姟鍣ㄦ祦閲忔秷鑰楄鏄庤В閲奭(./docs/faq/bandwidth.md)
- [鍚庡彴鍏ュ彛璐﹀瘑蹇樿閲嶇疆鏁欑▼](./docs/faq/login-reset.md)
- [Telegram 閫氱煡 Chat ID 鑾峰彇鏁欑▼](docs/faq/telegram-chat-id.md)
- [鎺ㄨ崘閰嶇疆鎻愰珮 Tron 鎵潡绋冲畾鎬р€硷笍](./docs/tron-grid/readme.md)
- [EVM RPC 鑺傜偣绋冲畾鎬ц鏄庢寚鍗椻€硷笍](./docs/faq/evm-rpc-endpoint.md)

## 鈿狅笍 閲嶈鎻愮ず

- **璁㈠崟浜ゆ槗寮轰緷璧栨椂闂?*锛氳纭繚鏈嶅姟鍣ㄦ椂闂村噯纭紝鍚﹀垯鍙兘瀵艰嚧璁㈠崟寮傚父
- **缃戠粶鐜瑕佹眰**锛氳纭繚鏈嶅姟鍣ㄧ綉缁滅幆澧冪ǔ瀹氾紝鍚﹀垯鍙兘褰卞搷鍔熻兘姝ｅ父杩愯

## 馃彎锔?绀惧尯浜ゆ祦

- **Telegram 缇ょ粍**锛歔https://t.me/BEpusdtChat](https://t.me/BEpusdtChat)
- **Telegram 棰戦亾**锛歔https://t.me/BEpusdtChannel](https://t.me/BEpusdtChannel)

## 馃檹 鑷磋阿

- [EPusdt](./docs/faq/epusdt.md)

## 馃専 Star 鍘嗗彶

[![Stargazers over time](https://starchart.cc/v03413/bepusdt.svg)](https://starchart.cc/v03413/bepusdt)

