### Structure

```json
{
  "type": "snell",
  "tag": "snell-in",

  ... // Listen Fields

  "psk": "my-pre-shared-key",
  "version": 4,
  "obfs_mode": "",
  "obfs_host": ""
}
```

### Listen Fields

See [Listen Fields](/configuration/shared/listen/) for details.

### Fields

#### psk

==Required==

The pre-shared key for authentication.

#### version

Snell protocol version. Must be `4` or `5`.

Defaults to `4`.

#### obfs_mode

Simple-obfs obfuscation mode.

One of `http` `tls`, or empty to disable.

#### obfs_host

The obfuscation hostname used for HTTP/TLS obfuscation.

Defaults to `bing.com` if not set.
