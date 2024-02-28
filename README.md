# GCP Always-Online Services

### Setup for always-online services deployed in Google Cloud
- Cloudflare Tunnel
- Uptime Kuma
    - Self-hosted CI/CD server
    - Self-hosted MicroK8s cluster

### How to Set Up
1. Clone repository
2. Create `.env` and replace:
    - tunnel token
    - shlink geolite key and api key

### Troubleshooting
1. Unable to access database from local
    - Check external IP
        - ie 112.200.194.34
    - Update firewall rule
        - https://console.cloud.google.com/net-security/firewall-manager/firewall-policies/list?authuser=1
