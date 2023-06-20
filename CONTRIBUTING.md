CONTRIBUTING.md # Contributing

## Build and deploy

```bash
rockcraft pack -v
sudo skopeo --insecure-policy copy oci-archive:sdcore-nrf_1.3_amd64.rock docker-daemon:sdcore-nrf:1.3
docker run sdcore-nrf:1.3
```
