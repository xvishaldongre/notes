# Web Development setup on Linux Mint 20.3 "Una" (via Ubuntu 20.04 LTS)

## Installing Node 

```bash
curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash - && \
sudo apt-get install -y nodejs
```

## PNPM using Corepack

```bash
corepack enable
corepack prepare pnpm@latest --activate
```