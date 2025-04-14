# Traefik Docker Compose

---

## Requirements

- Docker + Docker Compose
- mkcert

---

## Usage

### Local (HTTPS with mkcert)

```bash
docker-compose -f docker-compose.local.yml up -d
```

Make sure `traefik.docker.test` resolves to `127.0.0.1`. Add to `/etc/hosts` if needed.

➡️ https://traefik.docker.test

### Production

```bash
docker-compose -f docker-compose.prod.yml up -d
```

---

## Docs

- [Traefik](https://doc.traefik.io/traefik/)
- [mkcert](https://github.com/FiloSottile/mkcert)

