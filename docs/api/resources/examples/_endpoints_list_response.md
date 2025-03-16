<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2025-03-16T10:07:25Z",
			"description": "sample cloud endpoint",
			"domain": {
				"id": "rd_2uOVWfpHAoQEs3UKQixJaGgHjzg",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2uOVWfpHAoQEs3UKQixJaGgHjzg"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2uOVXFvXyO7QXK2cPHP8i11K9du",
			"metadata": "{\"environment\": \"staging\"}",
			"pooling_enabled": false,
			"proto": "https",
			"public_url": "https://endpoint-example2.com",
			"traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
			"type": "cloud",
			"updated_at": "2025-03-16T10:07:25Z",
			"uri": "https://api.ngrok.com/endpoints/ep_2uOVXFvXyO7QXK2cPHP8i11K9du",
			"url": "https://endpoint-example2.com"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-03-16T10:07:23Z",
			"hostport": "9e1c054190e6.ngrok.paid:443",
			"id": "ep_2uOVX0Tyv48PxUOZdfLYi0Ormex",
			"name": "command_line",
			"pooling_enabled": false,
			"principal": {
				"id": "usr_2uOVUhDsO7yyMWMoiH5fqrYXwX6",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://9e1c054190e6.ngrok.paid",
			"tunnel": {
				"id": "tn_2uOVX0Tyv48PxUOZdfLYi0Ormex",
				"uri": "https://api.ngrok.com/tunnels/tn_2uOVX0Tyv48PxUOZdfLYi0Ormex"
			},
			"tunnel_session": {
				"id": "ts_2uOVX79bb1XtIRJfxTpjUDIYoFh",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2uOVX79bb1XtIRJfxTpjUDIYoFh"
			},
			"type": "ephemeral",
			"updated_at": "2025-03-16T10:07:23Z",
			"upstream_url": "http://localhost:80",
			"url": "https://9e1c054190e6.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-03-16T10:07:21Z",
			"domain": {
				"id": "rd_2uOVWfpHAoQEs3UKQixJaGgHjzg",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2uOVWfpHAoQEs3UKQixJaGgHjzg"
			},
			"edge": {
				"id": "edgtls_2uOVWeMscFHx9uNeAcZyGZoakAq",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2uOVWeMscFHx9uNeAcZyGZoakAq"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2uOVWeCU5wuc6cvwlEsIK0vXCRZ",
			"pooling_enabled": false,
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2025-03-16T10:07:21Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
