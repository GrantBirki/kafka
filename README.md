# kafka 🚰

[![test](https://github.com/GrantBirki/kafka/actions/workflows/test.yml/badge.svg)](https://github.com/GrantBirki/kafka/actions/workflows/test.yml)

Spin up a full kafka stack with docker-compose

All of the original docs for this project can be found [here](docs/original.md)

## Quick Start 💻

To get started, simply run the following command:

```bash
make run
```

This will start the full docker-compose stack with the following:

- 3 zookeeper nodes
- 3 kafka nodes
- 1 kafka schema registry node
