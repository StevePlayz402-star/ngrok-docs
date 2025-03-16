<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"reserved_domains": [
		{
			"acme_challenge_cname_target": null,
			"certificate": null,
			"certificate_management_policy": {
				"authority": "letsencrypt",
				"private_key_type": "ecdsa"
			},
			"certificate_management_status": {
				"provisioning_job": {
					"error_code": null,
					"msg": "Managed certificate provisioning in progress.",
					"retries_at": null,
					"started_at": "2025-03-16T10:07:04Z"
				},
				"renews_at": null
			},
			"cname_target": "4knqktdwka2umyjjc.482va9ufv6vz76j2x.local-ngrok-cname.com",
			"created_at": "2025-03-16T10:07:04Z",
			"description": "Device 0001 Dashboard",
			"domain": "manage-0002.app.example.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2uOVUe2SPpLcTTpaA5tqwFUtvG4",
			"metadata": "{\"service\": \"dashboard\"}",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2uOVUe2SPpLcTTpaA5tqwFUtvG4"
		},
		{
			"acme_challenge_cname_target": null,
			"certificate": {
				"id": "cert_2uOVUc4D1okAlb1zOl9WsIRPwGX",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2uOVUc4D1okAlb1zOl9WsIRPwGX"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"cname_target": "2udamkamcl8pjmrff.482va9ufv6vz76j2x.local-ngrok-cname.com",
			"created_at": "2025-03-16T10:07:04Z",
			"domain": "myapp.mydomain.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2uOVUcbNm1fvpLw6SyAm4z0rpda",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2uOVUcbNm1fvpLw6SyAm4z0rpda"
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains"
}
```
