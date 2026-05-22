### 结构

```json
{
  "type": "snell",
  "tag": "snell-in",

  ... // 监听字段

  "psk": "my-pre-shared-key",
  "version": 4,
  "obfs_mode": "",
  "obfs_host": ""
}
```

### 监听字段

参阅 [监听字段](/zh/configuration/shared/listen/)。

### 字段

#### psk

==必填==

用于身份验证的预共享密钥。

#### version

Snell 协议版本，必须为 `4` 或 `5`。

默认为 `4`。

#### obfs_mode

simple-obfs 混淆模式。

可选 `http` `tls`，留空则禁用混淆。

#### obfs_host

用于 HTTP/TLS 混淆的主机名。

未设置时默认为 `bing.com`。
