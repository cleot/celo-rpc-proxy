# celo-rpc-proxy


## Running

```
docker compose up -d
```


## Update proxyd dependency

```bash
cd external/ethereum-optimism-infra
git checkout proxyd/v*  # Replace with desired version
```

Go back and commit the update:

```bash
cd ../..
git add external/ethereum-optimism-infra
git commit -m "Update proxyd to v*"  # Replace with actual version
```