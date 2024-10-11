<h1 align="center">StakeWise Distributed Validator Setup</h1>

This repo contains the [docker-compose](https://docs.docker.com/compose/) files needed to run one node in a [charon](https://github.com/ObolNetwork/charon) [Distributed Validator Cluster](https://docs.obol.tech/docs/int/key-concepts#distributed-validator-cluster).

A distributed validator node is a machine running:

- An Ethereum Execution client
- An Ethereum Consensus client
- An Ethereum Distributed Validator client
- An Ethereum Distributed Validator sidecar
- An Ethereum Validator client

# Examples

A default example configuration of a full validator node is found in the root `docker-compose.yml` file.

⚠️⚠️⚠️ **Important:**
The configurations provided are meant for demonstration purposes only and may not be suitable for production environments.
These examples are primarily intended for advanced users who are familiar with Docker and have a good understanding of execution and consensus clients.
Please exercise caution when using them and ensure that you thoroughly review and customize the configurations according to your specific requirements.

To run the default example, use the following command:

```sh
docker compose up
```
