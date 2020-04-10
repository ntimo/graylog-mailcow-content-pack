# graylog-mailcow-content-pack
A content pack for Graylog that creates magic mailcow insights.

# Requierments
- Mailcow
- In the configuration menu of your Graylog the `Message Filter Chain` has to be at prosition 1 or at least above the Pipeline Processor.
- You need to have a maxmind GeoIP Database setup for your Graylog at `/usr/local/etc/graylog/GeoLite2-City.mmdb`

# Installation
To install the content pack upload it to your Graylog at graylog.domain/system/contentpacks .

# Content pack includes:
- 5 Streams:
    - Mailcow
    - Mailcow - Postfix
    - Mailcow - Dovecot
    - Mailcow - Rspamd
    - Mailcow - Netfilter
- Dashboard:
    - mailcow
- Pipelines:
    - Mailcow
    - Mailcow - Postfix
    - Mailcow - Dovecot
    - Mailcow - Netfilter
- Grok patterns:
    - Postfix
    - Dovecot
    - Netfilter

# Screenshots

![Dashboard](https://raw.githubusercontent.com/ntimo/graylog-mailcow-content-pack/master/screenshots/dashboard.png)
