# bloxberg-monitoring-setup

TODO: Documentation

Default user name and password for Grafana is admin/foobar.

In order to run an example monitoring setup with a local bloxberg node (which won't be a validator) just run this sequence of docker-compose commands:

```bash
docker-compose -p monitoring up -d
docker-compose -p exporters -f exporters.yml up -d
docker-compose -p parity -f parity.yml up -d
```