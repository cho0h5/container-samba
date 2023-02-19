# container-samba
## usage
1. add environment variables in `.env`
```bash
cat << EOF > .env
SMB_USERNAME=yourname
SMB_USERPASSWD=yourpasswd
SMB_DATAPATH=/your/path
EOF
```
2. launch
```bash
docker compose up -d
```
