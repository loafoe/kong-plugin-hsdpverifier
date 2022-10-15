# kong-plugin-hsdpverifier

Verifies requests with the HSDP API Signing 

## configuration

```yaml
plugins:
  - name: hsdpverifier
```

## credentials

Credentials are read from the environment

| Field                     | Description                                             |
|---------------------------|---------------------------------------------------------|
| `HSDPVERIFIER_SHARED_KEY` | (Required) The shared key to look for                   |
| `HSDPVERIFIER_SECRET_KEY` | (Required) The secret key used for signature generation |

## license

License is MIT
