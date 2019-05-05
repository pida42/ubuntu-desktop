# Docker Ubuntu Desktop (with VNC server)

## Usage

1. Create data directories:

```
mkdir -p /mnt/ubuntu-desktop/data/root/.cache/mozilla/
mkdir -p /mnt/ubuntu-desktop/data/root/.mozilla/
chmod 0777 /mnt/ubuntu-desktop/data/root/.cache/mozilla/
chmod 0777 /mnt/ubuntu-desktop/data/root/.mozilla/
```

2. Change password in `.env` file.

3. Build:

```
docker-compose up -d --build
```

4. Logs (optional ;-)):

```
docker-compose logs -f
```

5. Connect

Connect using VNC (port 5900) or via browser [localhost:80](http://localhost).