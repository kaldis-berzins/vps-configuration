# VPS Configuration

# To deploy
1. `git clone https://github.com/kaldis-berzins/vps-configuration.git`
2. Get a cloudflare API token with Edit zone DNS permissions for domain
3. Fill in `.env` using `.env.example`
4. `docker compose up`
5. `docker compose scale server=3` for redundancy
6. To check logs use `docker compose logs -f` or `docker compose logs --tail`