# ipfs-api-reverse-proxy
NGINX configuration for IPFS API reverse proxy

1. Add a domain record, pointing subdomain ipfs to the Linux VPS.
2. Install latest version of IPFS, add CORS config and run ipfs daemon with --enable-pubsub-experiment
3. Install NGINX, ensure ports 80 and 443 are open
4. Move ipfs-api.conf to /etc/nginx/conf.d/ and restart NGINX
