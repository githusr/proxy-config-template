# Clash Meta Config

Copy `config.template.yaml` to `config.yaml` and modify the following places:

1. **`proxy-providers`**: Your subscription URLs and provider names, with `additional-suffix` if needed to distinguish same-named proxies across providers
2. **`__SECRET__`**: Your API secret for external controller
3. **Provider DNS** (optional): Convert `hosts` mappings to server rewrites using `override-expr`; configure `proxy-server-nameserver-policy` for proxy node resolution
4. **`rule-providers`** (optional): Custom rule URLs, with an `Authorization` header if needed

_References:
[Surfing](https://github.com/GitMetaio/Surfing),
[Clash-MIX](https://github.com/AXEVO/Clash-MIX),
[Meta Docs](https://wiki.metacubex.one)_
