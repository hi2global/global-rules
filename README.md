# 自用规则

```bash
rule-providers:
  ai:
    type: http
    behavior: domain
    url: https://raw.githubusercontent.com/hi2global/global-rules/main/rules/AI.txt
    path: ./rules/ai.yaml
    interval: 86400
  google:
    type: http
    behavior: domain
    url: https://raw.githubusercontent.com/hi2global/global-rules/main/rules/GoogleNoYTB.txt
    path: ./rules/google.yaml
    interval: 86400
  googlefcm:
    type: http
    behavior: domain
    url: https://raw.githubusercontent.com/hi2global/global-rules/main/rules/GoogleFCM.txt
    path: ./rules/googlefcm.yaml
    interval: 86400
  googleip:
    type: http
    behavior: ipcidr
    url: https://raw.githubusercontent.com/hi2global/global-rules/main/rules/GoogleIP.txt
    path: ./rules/googleip.yaml
    interval: 86400
  googlefcmip:
    type: http
    behavior: ipcidr
    url: https://raw.githubusercontent.com/hi2global/global-rules/main/rules/GoogleFCMIP.txt
    path: ./rules/googlefcmip.yaml
    interval: 86400
  youtube:
    type: http
    behavior: domain
    url: https://raw.githubusercontent.com/hi2global/global-rules/main/rules/YouTube.txt
    path: ./rules/youtube.yaml
    interval: 86400
  telegramipas:
    type: http
    behavior: ipcidr
    url: https://raw.githubusercontent.com/hi2global/global-rules/main/rules/TelegramIP-AS.txt
    path: ./rules/telegramipas.yaml
    interval: 86400
  telegramipna:
    type: http
    behavior: ipcidr
    url: https://raw.githubusercontent.com/hi2global/global-rules/main/rules/TelegramIP-NA.txt
    path: ./rules/telegramipna.yaml
    interval: 86400
  telegramipeu:
    type: http
    behavior: ipcidr
    url: https://raw.githubusercontent.com/hi2global/global-rules/main/rules/TelegramIP-EU.txt
    path: ./rules/telegramipeu.yaml
    interval: 86400
  steam:
    type: http
    behavior: domain
    url: https://raw.githubusercontent.com/hi2global/global-rules/main/rules/Steam.txt
    path: ./rules/steam.yaml
    interval: 86400
  steamdirect:
    type: http
    behavior: domain
    url: https://raw.githubusercontent.com/hi2global/global-rules/main/rules/SteamDirect.txt
    path: ./rules/steamdirect.yaml
    interval: 86400
  selfdirect:
    type: http
    behavior: domain
    url: https://raw.githubusercontent.com/hi2global/global-rules/main/rules/SelfDirect.txt
    path: ./rules/selfdirect.yaml
    interval: 86400
```

```bash
rules:
  - RULE-SET,selfdirect,🆖 本地直连,no-resolve
  - RULE-SET,steamdirect,🆖 本地直连,no-resolve
  - RULE-SET,reject,🛑 广告拦截
  - RULE-SET,ai,🔓 解锁,no-resolve
  - RULE-SET,youtube,📹 油管,no-resolve
  - RULE-SET,googlefcm,⚒️ 谷歌,no-resolve
  - RULE-SET,googlefcmip,⚒️ 谷歌,no-resolve
  - RULE-SET,google,⚒️ 谷歌,no-resolve
  - RULE-SET,googleip,⚒️ 谷歌,no-resolve
  - RULE-SET,telegramipas,🌏 亚洲,no-resolve
  - RULE-SET,telegramipna,🌎 美洲,no-resolve
  - RULE-SET,telegramipeu,🌍 欧洲,no-resolve
  - RULE-SET,steam,🎮 Steam,no-resolve
```
