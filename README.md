# Apple-Rule

Personal Clash/OpenClash rule lists for Apple Intelligence, Siri, and Apple Relay traffic.

Raw URL after publishing to GitHub:

```text
https://raw.githubusercontent.com/RocM301/Apple-Rule/refs/heads/main/Apple-AI.list
```

Example OpenClash rule provider:

```yaml
apple_ai:
  type: http
  behavior: classical
  format: text
  url: https://raw.githubusercontent.com/RocM301/Apple-Rule/refs/heads/main/Apple-AI.list
  path: ./ruleset/apple_ai.list
  interval: 86400
```
