
# Https Brahma Digivalet Com Api Datasourcesrequest

## Structure

`HttpsBrahmaDigivaletComApiDatasourcesrequest`

## Fields

| Name | Type | Tags | Description |
|  --- | --- | --- | --- |
| `name` | `string` | Required | - |
| `mtype` | `string` | Required | - |
| `url` | `string` | Required | - |
| `org` | `string` | Required | - |
| `access` | `string` | Required | - |
| `basic_auth` | `bool` | Required | - |
| `database` | `string` | Required | - |
| `user` | `string` | Required | - |
| `secure_json_data` | [`SecureJsonData`](../../doc/models/secure-json-data.md) | Required | - |

## Example (as JSON)

```json
{
  "name": "CMB",
  "type": "influxdb",
  "url": "https://dmon.digivalet.com",
  "Org": "shrey",
  "access": "proxy",
  "basicAuth": false,
  "database": "cmbdb",
  "user": "cmbuser",
  "secureJsonData": {
    "password": "123456"
  }
}
```

