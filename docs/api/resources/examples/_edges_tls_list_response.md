<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2025-03-16T10:07:30Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2uOVXuToM01nq20p5V3MGzTJ9IT",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2uOVXuToM01nq20p5V3MGzTJ9IT"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2uOVWjuUGn8akwkC6bfB4lTKdlo",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2uOVWjuUGn8akwkC6bfB4lTKdlo"
				},
				"enabled": true
			},
			"created_at": "2025-03-16T10:07:20Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2uOVWeMscFHx9uNeAcZyGZoakAq",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2uOVWeMscFHx9uNeAcZyGZoakAq"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
