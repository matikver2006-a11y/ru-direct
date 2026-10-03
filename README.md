# Российские сайты — мимо VPN

Страница: **https://matikver2006-a11y.github.io/ru-direct/**

Госуслуги, банки, маркетплейсы и всё российское — напрямую, остальное — через VPN.

- **Happ** — профиль маршрутизации одной кнопкой (`happ://routing/onadd/…`), можно добавить свои сайты.
- **Другие приложения** — готовые правила: v2rayNG, Streisand, Shadowrocket, Clash/mihomo, sing-box, Amnezia, Xray.

Файлы в `lists/`:

| Файл | Для чего |
|---|---|
| `ru-domains.txt` | 512 российских доменов (всё на .ru/.su/.рф входит целиком) |
| `ru-ipv4.txt` | 8 652 российские подсети IPv4 ([ipdeny.com](https://www.ipdeny.com/ipblocks/)) |
| `v2rayng-rules.json` | импорт правил в v2rayNG |
| `clash-rules.yaml` | `prepend-rules` для Clash Verge Rev / mihomo |
| `shadowrocket-rules.conf` | правила Shadowrocket |
| `sing-box-route.json` | фрагмент `route` для sing-box |
| `xray-routing.json` | правила маршрутизации Xray / v2ray |

В профиле нет серверов, ключей и подписок — только правила маршрутизации.
