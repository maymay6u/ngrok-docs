<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-07-28T10:08:21Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_30V0BNSNgBat8jLgy4YR4nWISE4",
        "uri": "https://api.ngrok.com/reserved_domains/rd_30V0BNSNgBat8jLgy4YR4nWISE4"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_30V0C0v51uVdJ6cuupDBEGR2XDn",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-07-28T10:08:21Z",
      "uri": "https://api.ngrok.com/endpoints/ep_30V0C0v51uVdJ6cuupDBEGR2XDn",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-07-28T10:08:19Z",
      "hostport": "f518427a9551.ngrok.paid:443",
      "id": "ep_30V0BmiFtkzWZRoRsaE2CyghN6w",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_30V05DekJqfUcQC6HA8kwsEbhZR",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://f518427a9551.ngrok.paid",
      "tunnel": {
        "id": "tn_30V0BmiFtkzWZRoRsaE2CyghN6w",
        "uri": "https://api.ngrok.com/tunnels/tn_30V0BmiFtkzWZRoRsaE2CyghN6w"
      },
      "tunnel_session": {
        "id": "ts_30V0BoilUq1SA2q7jgedYkfBhyr",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_30V0BoilUq1SA2q7jgedYkfBhyr"
      },
      "type": "ephemeral",
      "updated_at": "2025-07-28T10:08:19Z",
      "upstream_url": "http://localhost:80",
      "url": "https://f518427a9551.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-07-28T10:08:16Z",
      "domain": {
        "id": "rd_30V0BNSNgBat8jLgy4YR4nWISE4",
        "uri": "https://api.ngrok.com/reserved_domains/rd_30V0BNSNgBat8jLgy4YR4nWISE4"
      },
      "edge": {
        "id": "edgtls_30V0BSoyUYQPpdUjNN1qSVqrSE7",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_30V0BSoyUYQPpdUjNN1qSVqrSE7"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_30V0BMhpjE0GBheTrALDGsLrzYG",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-07-28T10:08:16Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
