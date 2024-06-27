# Ollama

Basic docker proxy for [Ollama](https://github.com/ollama/ollama/blob/main/docs/api.md) in our setup with Traefik and nginx to 
limit exposed end-points.

## Security

This setup does not come with any authentication, but relies on correctly 
configured server firewalls to protect the exposed end-points.
