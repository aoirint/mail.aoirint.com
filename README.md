# aoirint_mail_server

## Hash password

```shell
docker compose exec dovecot doveadm pw -s SHA512-CRYPT
```

## Backup

```shell
sudo 7z a "backups/aoirint_mail_server_volumes_$(date -u '+%Y-%m-%d_%H-%M-%S_utc').7z" volumes/
```
