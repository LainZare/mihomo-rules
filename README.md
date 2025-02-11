# 简介

`direct-domains`
`direct-apps`
`proxy-domains`
`hk-domains`

```yaml
rule-providers:
  my-direct-domains:
    type: http
    behavior: domain
    format: yaml
    path: ./rule_provider/direct-domains.yaml
    url: ""
    interval: 86400
  my-direct-apps:
    type: http
    behavior: classical
    format: yaml
    path: ./rule_provider/direct-apps.yaml
    url: ""
    interval: 86400
```
