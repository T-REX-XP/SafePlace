# SafePlace
WG-Easy+Undound+Pihole+NginxProxyManager+docker-compose

## How to setup?

1. Create file with name `.env` thac contains the following cntent:

`git clone https://github.com/T-REX-XP/SafePlace && cd SafePlace`

```
TZ=Europe/****
PI_HOLE_PASS=
WG_HOST=
WG_PASS=

DB_MYSQL_USER=
DB_MYSQL_PASSWORD=
```

2. Populate all variables 
  
3. Deploy it via the docker compose: 
   ```

   docker-compose up -d
   ```
   
   