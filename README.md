# ssl-check

Get notify before ssl certificates expire.

## Usage

```bash
cp .env.example .env
./bin/check
```

## Cron with runitor

```bash
runitor -uuid YOUR_UUID -- /path/to/ssl-check/bin/cron > /dev/null 2>&1
```
