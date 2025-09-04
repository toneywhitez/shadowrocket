> [!WARNING]
> Данный материал подготовлен в научно-технических и ознакомительных целях. Автор не несёт ответственности за иное использование предоставленного материала. Перед использованием убедитесь, что ваши действия соответствуют законодательству вашей страны. Использование в противоправных целях строго запрещено. Коммерческая эксплуатация предоставленного материала не допускается. 

# Конфиг файл для ShadowRocket 

## Ссылка на скачивание 
```bash
https://raw.githubusercontent.com/toneywhitez/shadowrocket/refs/heads/main/Conf_Zkeen.conf 
```
## Основа

**Zkeen domains**: https://github.com/jameszeroX/zkeen-domains

**Zkeen IP**: https://github.com/jameszeroX/zkeen-ip

_Базы обновляются раз в неделю по воскресеньям_

Спасибо за **конвертер** баз Anton111111: https://github.com/Anton111111/rule-lists, **мой форк**: https://github.com/toneywhitez/zkeen_rules 

## Категории, добавленные в конфиг
**Домены**:
- domains.list - домены, заблокированные в России
- other.list - домены, которые сами заблокировали подключения из России
- youtube.list - ютуб
- politic.list - новостные сайты на политическую тематику
- 2ip.io - IP ckecher (для проверки работы прокси, browserleaks.com также включен в базы из перечня выше)

**IP**:
- meta_ips.list - IP-подсети Meta
- telegram_ips.list - IP-подсети Telegram
- cloudflare_ips.list - IP-подсети CloudFlare
- discord_ips.list - IP-подсети голосовых серверов Discord

**+Добавлены порты для разблокировки звонков в TG & WA**

## Полный список баз Zkeen, можно добавить по своему желанию через Правило -> RULE-SET + ссылка на .list файл -> PROXY/DIRECT (или иное ваше правило)
<details>
 <summary>Домены</summary>

- domains.list - домены, заблокированные в России 

- other.list - домены, которые сами заблокировали подключения из России

- politic.list - новостные сайты

- youtube.list - ютуб
  </details>
  <details>
 <summary>IP</summary>
 
- amazon_ips.list - IP-подсети Amazon (AWS CloudFront)

- akami_ips.list 0 IP подсети AKAMI

- cdn77_ips.list - IP-подсети CDN77

- cloudflare_ips.list - IP-подсети CloudFlare

- digitalocean_ips.list - IP-подсети DigitalOcean

- discord_ips.list - IP-подсети голосовых серверов Discord

- fastly_ips.list - IP-подсети Fastly

- google_ips.list - IP-подсети Google

- hetzner_ips.list - IP-подсети Hetzner

- linode_ips.list - IP-подсети Linode

- ocarle_ips.list - IP подсети Oracle 

- meta_ips.list - IP-подсети Meta

- ovh_ips.list - IP-подсети OVH

- ru_ips.list - IP-подсети России

- telegram_ips.list - IP-подсети Telegram

- vultr_ips.list - IP подсети Vultr
    </details>
