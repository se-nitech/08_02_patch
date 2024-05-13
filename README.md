# patchのサンプル

起動

```bash
docker compose build
docker compose up -d
```

patchをあてる

```bash
docker compose exec -T myubuntu patch < main.py.diff
```

停止

```bash
docker compose down
```
