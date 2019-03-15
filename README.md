# prometheus-example

Prometheus example with grafana

Three containers are used:

- Prometheus
- Node exporter
- Grafana

Prometheus is auto setup and grafana is auto provisioned

## Demo

You can start docker-compose file and try it

```
$ docker-compose up -d
```

Now connect to on grafana `localhost:3000` connect with credentials:

- username: admin
- password: password

Go to dashboard and `Node exporter full`

You will see the data from the node-exporter container

## Licence

[MIT](https://fr.wikipedia.org/wiki/Licence_MIT)
