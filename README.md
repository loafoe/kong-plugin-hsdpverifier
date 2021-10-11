# kong-plugin-hsdpverifier

Verifies requests with the HSDP API Signing 

## configuration

```yaml
plugins:
  - name: hsdpverifier
    config:
       shared_key: XXX
       secret_key: YYY
```

## fields

* `config.shared_key` - (Required) The shared key to look for
* `config.secret_key` - (Required) The secret key used for signature generation

## license

License is MIT
