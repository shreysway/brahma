# Misc

```python
misc_controller = client.misc
```

## Class Name

`MiscController`


# Https Brahma Digivalet Com Api Datasources

```python
def https_brahma_digivalet_com_api_datasources(self,
                                              accept,
                                              body)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `accept` | `string` | Header, Required | - |
| `body` | [`HttpsBrahmaDigivaletComApiDatasourcesrequest`](../../doc/models/https-brahma-digivalet-com-api-datasourcesrequest.md) | Body, Required | - |

## Response Type

`void`

## Example Usage

```python
accept = 'application/json'
body = HttpsBrahmaDigivaletComApiDatasourcesrequest()
body.name = 'CMB'
body.mtype = 'influxdb'
body.url = 'https://dmon.digivalet.com'
body.org = 'shrey'
body.access = 'proxy'
body.basic_auth = False
body.database = 'cmbdb'
body.user = 'cmbuser'
body.secure_json_data = SecureJsonData()
body.secure_json_data.password = '123456'

result = misc_controller.https_brahma_digivalet_com_api_datasources(accept, body)
```

