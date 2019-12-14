# graylog-mailcow-content-pack
A content pack for Graylog that creates magic mailcow insights.

# Requierments
- Mailcow
- In the configuration menu of your Graylog the `Message Filter Chain` has to be at prosition 1 or at least above the Pipeline Processor.
- You need to have a maxmind GeoIP Database setup for your Graylog at `/usr/local/etc/graylog/GeoLite2-City.mmdb`

# Content pack includes:
- 3 Streams:
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
    - Mailcow - Netfilter
- Grok patterns:
    - Postfix

# Screenshots

![Dashboard](https://raw.githubusercontent.com/ntimo/graylog-mailcow-content-pack/master/screenshots/dashboard.png)
