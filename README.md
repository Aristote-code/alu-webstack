# Tasks Repository

This repository contains solutions to various tasks related to web infrastructure and configuration.

## Task 1: World Wide Web

### Description
Configure your domain zone to point subdomains to specific IP addresses and create a Bash script to display information about subdomains.

### Requirements
- Add the subdomain `www` to your domain and point it to your lb-01 IP.
- Add the subdomains `lb-01`, `web-01`, and `web-02` to your domain, each pointing to their respective IPs.
- Bash script must accept 2 arguments: `domain` and `subdomain`.
- Output format: `The subdomain [SUB_DOMAIN] is a [RECORD_TYPE] record and points to [DESTINATION]`.
- When only the `domain` parameter is provided, display information for its subdomains in the order `www`, `lb-01`, `web-01`, and `web-02`.
- Use `awk` and at least one Bash function.

### Usage Example
```bash
./0-world_wide_web holberton.online
./0-world_wide_web holberton.online web-02
