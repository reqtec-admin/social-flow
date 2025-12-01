# Social Flow

Get up and running with n8n on the following platforms:

* [Hetzner Cloud tutorial](https://docs.n8n.io/hosting/server-setups/hetzner/)

If you have questions after trying the tutorials, check out the [forums](https://community.n8n.io/).

## Prerequisites

Self-hosting n8n requires technical knowledge, including:

* Setting up and configuring servers and containers
* Managing application resources and scaling
* Securing servers and applications
* Configuring n8n

## What We Are Doing

Modifying configurations for our backbone n8n system to support automated social media flows.

This uses the ubuntu server on REQtec's hetzner account (n8n-social-flow).

## Let's Go

Edit the .env file.

## DNS Setup

Ensure you have configured DNS Entries (cloudflare)

Restart Docker Compose

```bash
sudo docker compose stop # if running
sudo docker compose up -d
sudo docker logs -f social-flow-caddy-caddy-1
```