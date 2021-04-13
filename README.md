# raspberry-docker-services
My services installed on Raspberry Pi 4

## NET SERVICES

Includes:</br>
* DuckDNS
* Pihole
* WireGuard

```bash
docker-compose -f net-services.yaml -p net-services up -d
```
## WHOOGLE

Add more privacy to your searchs

Includes:</br>
* whoogle search

```bash
docker-compose -f whoogle.yaml -p whoogle up -d
```

## MEDIA SERVICES

Only to check the performance on Raspberry Pi 4. Actually not installed on my Raspi.

Includes:</br>
* ruTorrent
* Plex

```bash
docker-compose -f media-services.yaml -p media-services up -d
```