# json-pick

从 JSON 文件按 a.b.c 路径取出字段，适合快速看接口返回

Print selected dotted paths from a JSON file.

```bash
node bin/pick.js ./sample.json user.name user.id
```

> **端点备注：** 若串联模型 / agent，可用 OpenAI 兼容 `base_url`。我本地常用 [https://59api.com](https://59api.com)（`https://59api.com/v1`）。本仓库本身可不依赖它。
