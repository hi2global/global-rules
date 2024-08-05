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
  googleip:
    type: http
    behavior: ipcidr
    url: https://raw.githubusercontent.com/hi2global/global-rules/main/rules/GoogleIP.txt
    path: ./rules/googleip.yaml
    interval: 86400
  github:
    type: http
    behavior: domain
    url: https://raw.githubusercontent.com/hi2global/global-rules/main/rules/Github.txt
    path: ./rules/github.yaml
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
  telegram:
    type: http
    behavior: domain
    url: https://raw.githubusercontent.com/hi2global/global-rules/main/rules/Telegram.txt
    path: ./rules/telegram.yaml
    interval: 86400
  tiktok:
    type: http
    behavior: domain
    url: https://raw.githubusercontent.com/hi2global/global-rules/main/rules/TikTok.txt
    path: ./ruleset/tiktok.yaml
    interval: 86400
  onedrive:
    type: http
    behavior: domain
    url: https://raw.githubusercontent.com/hi2global/global-rules/main/rules/OneDrive.txt
    path: ./ruleset/onedrive.yaml
    interval: 86400
  microsoft:
    type: http
    behavior: domain
    url: https://raw.githubusercontent.com/hi2global/global-rules/main/rules/Microsoft.txt
    path: ./ruleset/microsoft.yaml
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
  steamdirectip:
    type: http
    behavior: ipcidr
    url: https://raw.githubusercontent.com/hi2global/global-rules/main/rules/SteamDirectIP.txt
    path: ./rules/steamdirectip.yaml
    interval: 86400
```

```bash
rules:
  - RULE-SET,selfdirect,🆖 本地直连
  - RULE-SET,steamdirectip,🆖 本地直连
  - RULE-SET,steamdirect,🆖 本地直连
  - RULE-SET,steam,🎮 Steam
  - RULE-SET,ai,🎨 AI服务
  - RULE-SET,tiktok,🎶 TikTok
  - RULE-SET,youtube,📹 油管
  - RULE-SET,google,🔎 谷歌
  - RULE-SET,googleip,🔎 谷歌
  - RULE-SET,googlefcmip,🔎 谷歌
  - RULE-SET,github,🛠️ Github
  - RULE-SET,microsoft,Ⓜ️ 微软
  - RULE-SET,onedrive,Ⓜ️ 微软
  - RULE-SET,telegramipas,📲 电报
  - RULE-SET,telegramipna,📲 电报
  - RULE-SET,telegramipeu,📲 电报
  - RULE-SET,telegram,📲 电报
```
