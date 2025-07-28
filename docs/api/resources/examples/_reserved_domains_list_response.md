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
          "started_at": "2025-07-28T10:08:00Z"
        },
        "renews_at": null
      },
      "cname_target": "4knqktdwka2umyjjc.44mmgvbwwhszr1b7c.local-ngrok-cname.com",
      "created_at": "2025-07-28T10:08:00Z",
      "description": "Device 0001 Dashboard",
      "domain": "manage-0002.app.example.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_30V09MtVPAy7jdfvokmGnZ2sdYq",
      "is_dev": false,
      "metadata": "{\"service\": \"dashboard\"}",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_30V09MtVPAy7jdfvokmGnZ2sdYq"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": {
        "id": "cert_30V09Mu6SMfgqo9LZhuIdrsE7zL",
        "uri": "https://api.ngrok.com/tls_certificates/cert_30V09Mu6SMfgqo9LZhuIdrsE7zL"
      },
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": "2udamkamcl8pjmrff.44mmgvbwwhszr1b7c.local-ngrok-cname.com",
      "created_at": "2025-07-28T10:08:00Z",
      "domain": "myapp.mydomain.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_30V09MQLPEAkhE6jB2ck5uy4leG",
      "is_dev": false,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_30V09MQLPEAkhE6jB2ck5uy4leG"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": null,
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": null,
      "created_at": "2025-07-28T10:07:30Z",
      "description": "Your dev domain",
      "domain": "hip-eft-notable.ngrok-free.dev",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_30V05gcmIsre4bAKZP6JS6zg6t1",
      "is_dev": true,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_30V05gcmIsre4bAKZP6JS6zg6t1"
    }
  ],
  "uri": "https://api.ngrok.com/reserved_domains"
}
```
