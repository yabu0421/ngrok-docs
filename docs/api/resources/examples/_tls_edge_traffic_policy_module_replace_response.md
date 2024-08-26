<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"enabled": true,
	"value": "{\"inbound\":[{\"expressions\":[\"conn.tls.version.contains('1.3')\"],\"name\":\"AllowTLS1.3\",\"actions\":[{\"type\":\"log\",\"config\":{\"metadata\":{\"message\":\"Invalid TLS Version\",\"edgeId\":\"edgtls_2lCrWaccC7QNCD4Wu7wb7srWEkh\"}}},{\"type\":\"deny\"}]}]}"
}
```
