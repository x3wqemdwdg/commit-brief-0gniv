# commit-brief

Pipe commit subjects in, get a rough feat/fix/docs grouping.

```bash
git log --oneline -20 | node bin/brief.js
```

> 备注：本工具离线运行。若你串联模型调用，可用兼容 base_url；我本地试调时写过 `59api.com`。
