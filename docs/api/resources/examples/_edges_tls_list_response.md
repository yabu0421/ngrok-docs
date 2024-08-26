<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2024-08-26T17:55:30Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2lCrWUZyBhTM256X85cDldFlLKf",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2lCrWUZyBhTM256X85cDldFlLKf"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2lCrV4J6uIhJDAWeDdAuTgWhhpy",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2lCrV4J6uIhJDAWeDdAuTgWhhpy"
				},
				"enabled": true
			},
			"created_at": "2024-08-26T17:55:19Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2lCrV8qWQsN7JLngx48xtcTppEl",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2lCrV8qWQsN7JLngx48xtcTppEl"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
