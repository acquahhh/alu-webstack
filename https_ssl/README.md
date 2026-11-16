# HTTPS SSL

Configure DNS subdomains, terminate SSL on HAProxy and redirect HTTP traffic to HTTPS.

| File | Description |
|---|---|
| `0-world_wide_web` | Bash script that displays the record type and destination of a domain's subdomains |
| `1-haproxy_ssl_termination` | HAProxy config that terminates SSL for `www` on port 443 |
| `2-redirect_http_to_https` | HAProxy config that also redirects HTTP to HTTPS with a 301 |
