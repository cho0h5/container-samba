# container-samba
## usage
1. add environment variables in `.env`
```bash
cat << EOF > .env
SMB_USERNAME=yourname
SMB_UID=2000
SMB_GID=2000
SMB_USERPASSWD=yourpasswd
SMB_DATAPATH=/your/path
SMB_PORT=445
EOF
```
2. launch
```bash
docker compose up -d
```
