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

## sing-box / Momo

Native sing-box rule-set source format:

```text
https://raw.githubusercontent.com/RocM301/Apple-Rule/refs/heads/main/Apple-AI.json
```

Example:

```json
{
  "tag": "apple-ai",
  "type": "remote",
  "format": "source",
  "url": "https://raw.githubusercontent.com/RocM301/Apple-Rule/refs/heads/main/Apple-AI.json",
  "download_detour": "🎯 全球直连"
}
```

## Icons

The icon assets are mirrored in `icons/` and the group-name mapping is available here:

```text
https://raw.githubusercontent.com/RocM301/Apple-Rule/main/icons.json
```

Each path in `icons.json` resolves under:

```text
https://raw.githubusercontent.com/RocM301/Apple-Rule/main/
```

sing-box does not consume icon metadata itself. A dashboard or wrapper can use this mapping to display the icons for the corresponding outbound groups.
