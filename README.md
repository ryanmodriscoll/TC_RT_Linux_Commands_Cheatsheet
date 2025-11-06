# TC_RT_Linux_Commands_Cheatsheet
Random commands

## Prerequisites

- Docker ≥ 24 (or your deps)
- Git ≥ 2.40

## Containers

```bash
# Clone and enter
git clone https://github.com/Beckhoff/TC_XAR_Container_Sample && cd tester
```

```bash
# Build
sudo docker build --secret id=apt,src=./apt-config/bhf.conf --network host -t tc31-xar-base . .
```

```bash
# Run
sudo docker compose up -d
```

```bash
# Check status
sudo docker compose ps
```

```bash
# List all files in a dir
ls -l
```

```bash
# Delete all files in a dir
sudo rm -rf ~/work/TC_XAR_Container_Sample/{*,.*} 2>/dev/null
```

```bash
# List all Docker related services
sudo docker ps -a
```

<details>
 
## License

MIT © <YEAR> <OWNER>

