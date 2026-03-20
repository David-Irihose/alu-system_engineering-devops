# Firewall Configuration

This directory contains tasks related to configuring a firewall using UFW (Uncomplicated Firewall).

## Task: 0-block_all_incoming_traffic_but

This script configures the firewall to:

- Block all incoming traffic by default
- Allow outgoing traffic
- Allow only the following incoming TCP ports:
  - 22 (SSH)
  - 80 (HTTP)
  - 443 (HTTPS)

This ensures basic server security by restricting access to only necessary services.
