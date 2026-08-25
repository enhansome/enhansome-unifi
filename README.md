# Awesome UniFi with stars

<div align="center">
  <a href="https://ui.com"><img width="400" src="media/logo.svg" alt="Awesome UniFi"></a>
</div>

> A curated list of awesome tools, libraries, and resources for UniFi and Ubiquiti networking products.

UniFi is a line of networking hardware and software by Ubiquiti Inc., including wireless access points, switches, routers (Dream Machine series), cameras (Protect), and access control systems. This list collects the best community-created tools to enhance your UniFi experience.

## Contents

* [Official Resources](#official-resources)
* [API Libraries](#api-libraries)
  * [Python](#python)
  * [Node.js / JavaScript](#nodejs--javascript)
  * [Go](#go)
  * [PHP](#php)
  * [.NET / C#](#net--c)
  * [Ruby](#ruby)
* [Controller & Management](#controller--management)
* [Docker Images](#docker-images)
* [Monitoring & Metrics](#monitoring--metrics)
  * [Prometheus & Grafana](#prometheus--grafana)
  * [Zabbix](#zabbix)
  * [Other Monitoring](#other-monitoring)
* [Home Automation](#home-automation)
  * [Home Assistant](#home-assistant)
  * [Homebridge / HomeKit](#homebridge--homekit)
  * [Other Platforms](#other-platforms)
* [UniFi Protect](#unifi-protect)
* [UniFi Access](#unifi-access)
* [Network Automation & IaC](#network-automation--iac)
* [Security Tools](#security-tools)
* [DNS & DDNS](#dns--ddns)
* [VPN & WireGuard](#vpn--wireguard)
* [Backup Tools](#backup-tools)
* [Guest Portal & Vouchers](#guest-portal--vouchers)
* [Dream Machine Utilities](#dream-machine-utilities)
* [EdgeRouter / EdgeOS](#edgerouter--edgeos)
* [MCP Servers](#mcp-servers)
* [Guides & Documentation](#guides--documentation)

***

## Official Resources

* [Ubiquiti Community](https://community.ui.com) - Official community forums.
* [UniFi Design Center](https://design.ui.com) - Official network design tool.
* [UniFi Downloads](https://ui.com/download/releases/network-server) - Official software downloads.
* [UniFi Help Center](https://help.ui.com) - Official documentation.

## API Libraries

### Python

* [ubiquiti-community/py-unifi](https://github.com/ubiquiti-community/py-unifi) ⭐ 21 | 🐛 6 | 🌐 Python | 📅 2026-07-20 - Python UniFi API Client.
* [tnware/unifi-controller-api](https://github.com/tnware/unifi-controller-api) ⭐ 17 | 🐛 3 | 🌐 Python | 📅 2026-06-15 - Python client library for interacting with Ubiquiti UniFi Network Controllers.

### Node.js / JavaScript

* [jens-maus/node-unifi](https://github.com/jens-maus/node-unifi) ⭐ 161 | 🐛 33 | 🌐 JavaScript | 📅 2026-05-29 - Node.js class for querying and controlling UniFi Controllers across all hardware platforms.
* [thib3113/unifi-client](https://github.com/thib3113/unifi-client) ⭐ 46 | 🐛 13 | 🌐 TypeScript | 📅 2026-08-21 - Node.js client for UniFi products.

### Go

* [paultyng/go-unifi](https://github.com/paultyng/go-unifi) ⚠️ Archived - UniFi Controller API SDK for Go.
* [unpoller/unifi](https://github.com/unpoller/unifi) ⭐ 152 | 🐛 2 | 🌐 Go | 📅 2026-08-24 - Go library to grab data from a Ubiquiti UniFi Controller (companion library used by UnPoller).
* [ClifHouck/unified](https://github.com/ClifHouck/unified) ⭐ 17 | 🐛 1 | 🌐 Go | 📅 2026-02-12 - Unofficial UniFi Network and Protect API client and CLI written in Go.

### PHP

* [Art-of-WiFi/UniFi-API-client](https://github.com/Art-of-WiFi/UniFi-API-client) ⭐ 1,343 | 🐛 7 | 🌐 PHP | 📅 2026-07-27 - PHP API client class to interact with Ubiquiti's UniFi Controller API.

### .NET / C\#

* [KoenZomers/UniFiApi](https://github.com/KoenZomers/UniFiApi) ⭐ 76 | 🐛 1 | 🌐 C# | 📅 2026-07-11 - API in .NET 9 to fetch data from an on premises Ubiquiti UniFi Controller.
* [schwoi/UnifiClient](https://github.com/schwoi/UnifiClient) ⭐ 19 | 🐛 3 | 🌐 C# | 📅 2024-11-03 - .NET Standard wrapper library for the Ubiquiti UniFi Controller.
* [dotMorten/UnifiClient](https://github.com/dotMorten/UnifiClient) ⭐ 15 | 🐛 0 | 🌐 C# | 📅 2023-04-28 - .NET library for the Ubiquiti UniFi REST and WebSocket APIs.

### Ruby

* [hculap/unifi-api](https://github.com/hculap/unifi-api) ⭐ 13 | 🐛 2 | 🌐 Ruby | 📅 2023-05-04 - Ruby client for the UniFi Controller API.

## Controller & Management

* [unifi-utilities/unifios-utilities](https://github.com/unifi-utilities/unifios-utilities) ⭐ 4,363 | 🐛 0 | 🌐 Shell | 📅 2026-07-31 - Community collection of utilities and enhancements for UniFi OS.
* [Art-of-WiFi/UniFi-API-browser](https://github.com/Art-of-WiFi/UniFi-API-browser) ⭐ 1,258 | 🐛 8 | 🌐 PHP | 📅 2026-02-24 - Tool to browse data exposed by Ubiquiti's UniFi Controller API.
* [Ozark-Connect/NetworkOptimizer](https://github.com/Ozark-Connect/NetworkOptimizer) ⭐ 976 | 🐛 66 | 🌐 C# | 📅 2026-08-25 - Self-hosted performance optimization and security audit tool for UniFi Networks.
* [unofficial-unifi/unifi-pfsense](https://github.com/unofficial-unifi/unifi-pfsense) ⭐ 785 | 🐛 24 | 🌐 Shell | 📅 2026-03-30 - Install the UniFi Controller software on pfSense and other FreeBSD systems.
* [stevejenkins/unifi-linux-utils](https://github.com/stevejenkins/unifi-linux-utils) ⭐ 718 | 🐛 24 | 🌐 Shell | 📅 2023-06-30 - Helpful Linux/Unix scripts for admins of Ubiquiti UniFi wireless products.
* [Crosstalk-Solutions/unifi-toolkit](https://github.com/Crosstalk-Solutions/unifi-toolkit) ⭐ 507 | 🐛 11 | 🌐 Python | 📅 2026-04-27 - Suite of tools for UniFi network management.
* [hyperb1iss/unifly](https://github.com/hyperb1iss/unifly) ⭐ 247 | 🐛 1 | 🌐 Rust | 📅 2026-08-07 - Rust CLI and TUI for managing UniFi controllers via dual Integration and Legacy APIs with real-time WebSocket events.
* [Unifi-Tools/UFiber.Configurator](https://github.com/Unifi-Tools/UFiber.Configurator) ⭐ 215 | 🐛 32 | 🌐 C# | 📅 2024-08-18 - Configuration tool for managing and provisioning Ubiquiti UFiber GPON devices.
* [ZSamuels28/UnifiClientCheck-Docker](https://github.com/ZSamuels28/UnifiClientCheck-Docker) ⭐ 53 | 🐛 1 | 🌐 Go | 📅 2026-07-17 - Monitor UniFi networks for new devices with Telegram or Ntfy alerts.
* [veteranbv/unifi-client-updater](https://github.com/veteranbv/unifi-client-updater) ⭐ 50 | 🐛 0 | 🌐 Python | 📅 2025-04-01 - Bulk update client names and metadata across UniFi sites.
* [scyto/docker-UnifiBrowser](https://github.com/scyto/docker-UnifiBrowser) ⭐ 41 | 🐛 0 | 🌐 PHP | 📅 2026-06-11 - Dockerized version of the UniFi API Browser.
* [57/unifidash](https://github.com/57/unifidash) ⭐ 22 | 🐛 0 | 🌐 PowerShell | 📅 2025-05-24 - CLI leveraging private gateway APIs for network telemetry, DPI, and topology.

## Docker Images

* [jacobalberty/unifi-docker](https://github.com/jacobalberty/unifi-docker) ⭐ 2,614 | 🐛 15 | 🌐 Shell | 📅 2026-08-21 - UniFi Docker files.
* [linuxserver/docker-unifi-network-application](https://github.com/linuxserver/docker-unifi-network-application) ⭐ 1,165 | 🐛 7 | 🌐 Dockerfile | 📅 2026-08-07 - LinuxServer.io Docker image for UniFi Network Application.
* [goofball222/unifi](https://github.com/goofball222/unifi) ⭐ 321 | 🐛 4 | 🌐 Shell | 📅 2026-08-24 - UniFi Docker Container.
* [Nico640/docker-unms](https://github.com/Nico640/docker-unms) ⭐ 277 | 🐛 28 | 🌐 Dockerfile | 📅 2026-06-04 - All-in-one Docker image for Ubiquiti UISP (formerly UNMS) - supports x86\_64 and ARM.
* [GiuseppeGalilei/Unifi-Network-Application](https://github.com/GiuseppeGalilei/Unifi-Network-Application) ⭐ 197 | 🐛 11 | 🌐 Shell | 📅 2024-05-12 - Easily deploy UniFi Network Application on Docker.
* [jcberthon/unifi-docker](https://github.com/jcberthon/unifi-docker) ⭐ 30 | 🐛 0 | 🌐 Shell | 📅 2024-06-23 - UniFi Controller Docker image and compose.

## Monitoring & Metrics

### Prometheus & Grafana

* [unpoller/unpoller](https://github.com/unpoller/unpoller) ⭐ 2,692 | 🐛 6 | 🌐 Go | 📅 2026-08-24 - Collect all UniFi Controller, site, device, and client data and export to InfluxDB or Prometheus.
* [timothystewart6/unpoller-unifi](https://github.com/timothystewart6/unpoller-unifi) ⭐ 133 | 🐛 1 | 📅 2026-05-21 - Ready-to-run Docker Compose stack for monitoring UniFi networks with UnPoller, Prometheus, and Grafana (third-party deployment stack).
* [unpoller/dashboards](https://github.com/unpoller/dashboards) ⭐ 44 | 🐛 16 | 🌐 Shell | 📅 2026-06-15 - Pre-built Grafana dashboards for visualizing UnPoller data (companion dashboards).
* [zygiss/snmp-exporter-unifi](https://github.com/zygiss/snmp-exporter-unifi) ⭐ 23 | 🐛 0 | 📅 2023-07-15 - Prometheus SNMP exporter generator and SNMP configs for UniFi access points.

### Zabbix

* [patricegautier/unifiZabbix](https://github.com/patricegautier/unifiZabbix) ⭐ 223 | 🐛 27 | 🌐 Shell | 📅 2026-01-24 - Comprehensive Zabbix templates covering all UniFi device types.
* [MassimilianoPasquini97/zbx\_unifi\_network\_api](https://github.com/MassimilianoPasquini97/zbx_unifi_network_api) ⭐ 46 | 🐛 9 | 📅 2025-11-29 - UniFi Network Zabbix Template.

### Other Monitoring

* [carverauto/serviceradar](https://github.com/carverauto/serviceradar) ⭐ 913 | 🐛 306 | 🌐 Elixir | 📅 2026-08-25 - Zero-trust open-source network management and observability platform with UniFi support.
* [jmasarweh/Unifi-Log-Insights](https://github.com/jmasarweh/Unifi-Log-Insights) ⭐ 264 | 🐛 35 | 🌐 Python | 📅 2026-06-30 - Self-hosted real-time syslog analysis for UniFi gateways with GeoIP enrichment, threat intelligence, and interactive dashboards.

## Home Automation

### Home Assistant

* [hassio-addons/addon-unifi](https://github.com/hassio-addons/addon-unifi) ⭐ 376 | 🐛 4 | 🌐 Dockerfile | 📅 2026-08-21 - UniFi Network Application - Home Assistant Community Add-ons.
* [imhotep/hass-unifi-access](https://github.com/imhotep/hass-unifi-access) ⭐ 184 | 🐛 1 | 🌐 Python | 📅 2026-07-21 - UniFi Access Integration for Home Assistant.
* [elad-bar/ha-edgeos](https://github.com/elad-bar/ha-edgeos) ⭐ 146 | 🐛 30 | 🌐 Python | 📅 2025-09-20 - Home Assistant integration for Ubiquiti EdgeOS routers.
* [ufozone/ha-unifi-voucher](https://github.com/ufozone/ha-unifi-voucher) ⭐ 80 | 🐛 1 | 🌐 Python | 📅 2026-08-22 - UniFi Hotspot Manager Integration.
* [sirkirby/unifi-network-rules](https://github.com/sirkirby/unifi-network-rules) ⭐ 62 | 🐛 3 | 🌐 Python | 📅 2026-06-01 - Manage, backup, and automate your UDM firewall policies in Home Assistant.
* [ruaan-deysel/ha-unifi-insights](https://github.com/ruaan-deysel/ha-unifi-insights) ⭐ 39 | 🐛 5 | 🌐 Python | 📅 2026-08-25 - Comprehensive Home Assistant custom integration for UniFi Network and Protect.
* [biofects/HA-Unifi-Speedtest](https://github.com/biofects/HA-Unifi-Speedtest) ⭐ 31 | 🐛 0 | 🌐 Python | 📅 2026-08-24 - Real-time speed test monitoring for UniFi networks in Home Assistant.
* [patagonaa/homeassistant-unifi-led](https://github.com/patagonaa/homeassistant-unifi-led) ⭐ 17 | 🐛 0 | 🌐 C# | 📅 2025-03-31 - Control UniFi access point LEDs via Home Assistant.

### Homebridge / HomeKit

* [hjdhjd/homebridge-unifi-protect](https://github.com/hjdhjd/homebridge-unifi-protect) ⭐ 1,776 | 🐛 2 | 🌐 TypeScript | 📅 2026-07-19 - Complete HomeKit integration for all UniFi Protect device types with full support for HomeKit Secure Video.
* [hjdhjd/homebridge-unifi-access](https://github.com/hjdhjd/homebridge-unifi-access) ⭐ 71 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-10 - UniFi Access plugin for HomeKit (Homebridge).

### Other Platforms

* [ioBroker.unifi](https://github.com/iobroker-community-adapters/ioBroker.unifi) ⭐ 67 | 🐛 67 | 🌐 JavaScript | 📅 2026-08-20 - ioBroker adapter for UniFi network devices.

## UniFi Protect

* [keshavdv/unifi-cam-proxy](https://github.com/keshavdv/unifi-cam-proxy) ⭐ 1,869 | 🐛 4 | 🌐 Python | 📅 2026-08-25 - Enable non-Ubiquiti cameras to work with UniFi NVR.
* [ep1cman/unifi-protect-backup](https://github.com/ep1cman/unifi-protect-backup) ⭐ 865 | 🐛 18 | 🌐 Python | 📅 2026-05-11 - Back up UniFi Protect event clips in realtime to local or cloud storage.
* [danielfernau/unifi-protect-video-downloader](https://github.com/danielfernau/unifi-protect-video-downloader) ⭐ 512 | 🐛 48 | 🌐 Python | 📅 2026-07-10 - Download video footage from UniFi Protect locally.
* [hjdhjd/unifi-protect](https://github.com/hjdhjd/unifi-protect) ⭐ 405 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-21 - Comprehensive UniFi Protect API implementation in TypeScript.
* [petergeneric/unifi-protect-remux](https://github.com/petergeneric/unifi-protect-remux) ⭐ 339 | 🐛 0 | 🌐 Rust | 📅 2026-06-15 - Converts Ubiquiti's proprietary .ubv files into standard MP4 files.

## UniFi Access

* [hjdhjd/unifi-access](https://github.com/hjdhjd/unifi-access) ⭐ 51 | 🐛 0 | 🌐 TypeScript | 📅 2026-01-23 - Comprehensive implementation of the UniFi Access API.
* [keithah/unifi-access-airbnb](https://github.com/keithah/unifi-access-airbnb) ⭐ 32 | 🐛 2 | 🌐 Python | 📅 2026-08-13 - Integrates UniFi Access with Airbnb reservations using ICS file or Hostex API.
* [matejgordon/unipyAccess](https://github.com/matejgordon/unipyAccess) ⭐ 21 | 🐛 0 | 🌐 Python | 📅 2025-11-12 - Python connector for UniFi Access.
* [phamels/unifi\_access\_unlocker](https://github.com/phamels/unifi_access_unlocker) ⭐ 10 | 🐛 2 | 🌐 Python | 📅 2023-06-20 - Unlock UniFi Access doors using their own API.

## Network Automation & IaC

* [paultyng/terraform-provider-unifi](https://github.com/paultyng/terraform-provider-unifi) ⚠️ Archived - Terraform provider for UniFi.
* [pulumiverse/pulumi-unifi](https://github.com/pulumiverse/pulumi-unifi) ⭐ 22 | 🐛 2 | 🌐 Makefile | 📅 2026-08-07 - Pulumi provider for UniFi network gear.

## Security Tools

* [wolffcatskyy/crowdsec-blocklist-import](https://github.com/wolffcatskyy/crowdsec-blocklist-import) ⭐ 338 | 🐛 2 | 🌐 Python | 📅 2026-07-22 - Import 120k+ IPs from 36 free threat feeds into CrowdSec decisions for UniFi.
* [jmasarweh/Unifi-Log-Insights](https://github.com/jmasarweh/Unifi-Log-Insights) ⭐ 264 | 🐛 35 | 🌐 Python | 📅 2026-06-30 - Real-time syslog analysis for UniFi gateways with AbuseIPDB threat scoring, threat maps, and firewall policy management.
* [wolffcatskyy/crowdsec-unifi-bouncer](https://github.com/wolffcatskyy/crowdsec-unifi-bouncer) ⭐ 39 | 🐛 0 | 🌐 Go | 📅 2026-07-22 - Install and persist the official CrowdSec firewall bouncer on UniFi OS devices.
* [trek-e/unifi-security-report](https://github.com/trek-e/unifi-security-report) ⭐ 25 | 🐛 15 | 🌐 Python | 📅 2026-04-13 - Containerized service that monitors UniFi network logs and delivers plain-English reports.
* [coolcat1575/netwatcher](https://github.com/coolcat1575/netwatcher) ⭐ 18 | 🐛 1 | 🌐 Python | 📅 2025-07-24 - Monitor your network for unknown MAC addresses using data from UniFi.
* [LordOfPolls/Unifi-Rampart](https://github.com/LordOfPolls/Unifi-Rampart) ⭐ 17 | 🐛 0 | 🌐 Rust | 📅 2026-07-05 - Automated threat intelligence for UniFi firewalls - syncs IP lists from Spamhaus, Firehol, abuse.ch.
* [shrisha/SilenceTheLAN](https://github.com/shrisha/SilenceTheLAN) ⭐ 10 | 🐛 0 | 🌐 Swift | 📅 2026-04-10 - iOS app to manage UniFi Firewall policies created for kids' downtime.
* [wolffcatskyy/crowdsec-unifi-parser](https://github.com/wolffcatskyy/crowdsec-unifi-parser) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2026-03-16 - CrowdSec parsers and iptables LOG rules for UniFi Dream Machines.
* [wolffcatskyy/crowdsec-unifi-suite](https://github.com/wolffcatskyy/crowdsec-unifi-suite) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2026-03-16 - One-command installer for CrowdSec + UniFi security stack (bouncer + parser + blocklist-import).

## DNS & DDNS

* [willswire/unifi-ddns](https://github.com/willswire/unifi-ddns) ⭐ 1,280 | 🐛 5 | 🌐 TypeScript | 📅 2026-08-23 - Cloudflare DDNS (Dynamic DNS) support for UniFi OS.
* [kashalls/external-dns-unifi-webhook](https://github.com/kashalls/external-dns-unifi-webhook) ⭐ 320 | 🐛 2 | 🌐 Go | 📅 2026-08-24 - External-DNS Webhook to manage UniFi DNS Records.
* [ymichel/dnsmasqAdBlockUDM](https://github.com/ymichel/dnsmasqAdBlockUDM) ⭐ 14 | 🐛 2 | 🌐 Shell | 📅 2025-01-29 - Dnsmasq based Ad blocking for UniFi equipment (UDM-SE and UDM-PRO).

## VPN & WireGuard

* [SierraSoftworks/tailscale-udm](https://github.com/SierraSoftworks/tailscale-udm) ⭐ 1,687 | 🐛 1 | 🌐 Shell | 📅 2026-08-17 - Run Tailscale on your UniFi Dream Machine.
* [WireGuard/wireguard-vyatta-ubnt](https://github.com/WireGuard/wireguard-vyatta-ubnt) ⭐ 1,485 | 🐛 63 | 🌐 Shell | 📅 2026-04-01 - WireGuard for Ubiquiti Devices.
* [peacey/split-vpn](https://github.com/peacey/split-vpn) ⭐ 842 | 🐛 40 | 🌐 Shell | 📅 2023-07-10 - Policy-based split tunnel VPN for UniFi OS gateways.
* [jamesog/tailscale-edgeos](https://github.com/jamesog/tailscale-edgeos) ⭐ 399 | 🐛 3 | 🌐 Shell | 📅 2024-02-14 - Running Tailscale on Ubiquiti EdgeOS.
* [tusc/wireguard-kmod](https://github.com/tusc/wireguard-kmod) ⭐ 343 | 🐛 11 | 🌐 Shell | 📅 2023-03-02 - WireGuard for UDM series routers.
* [evie-lau/Unifi-gateway-wpa-supplicant](https://github.com/evie-lau/Unifi-gateway-wpa-supplicant) ⭐ 107 | 🐛 4 | 📅 2026-07-10 - Set up wpa\_supplicant on UniFi Gateways to bypass the AT\&T modem.
* [vchrizz/ER-wizard-WireGuard](https://github.com/vchrizz/ER-wizard-WireGuard) ⭐ 107 | 🐛 3 | 🌐 HTML | 📅 2025-08-13 - WireGuard Wizard for Ubiquiti EdgeMAX Devices.

## Backup Tools

* [zhangyoufu/unifi-backup-decrypt](https://github.com/zhangyoufu/unifi-backup-decrypt) ⭐ 243 | 🐛 2 | 🌐 Shell | 📅 2024-05-02 - Decrypt UniFi Network Application backup (.unf to .zip).
* [psitem/edgerouter-backup](https://github.com/psitem/edgerouter-backup) ⭐ 77 | 🐛 0 | 🌐 Shell | 📅 2023-03-08 - EdgeRouter to Git repo backup scripts.

## Guest Portal & Vouchers

* [glenndehaan/unifi-voucher-site](https://github.com/glenndehaan/unifi-voucher-site) ⭐ 301 | 🐛 1 | 🌐 EJS | 📅 2026-07-15 - Web platform for generating and managing UniFi network guest vouchers.
* [DJM0/unifi-voucher-generator](https://github.com/DJM0/unifi-voucher-generator) ⚠️ Archived - Generate printable UniFi Hotspot vouchers via the Controller API.
* [etiennecollin/unifi-voucher-manager](https://github.com/etiennecollin/unifi-voucher-manager) ⭐ 78 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-26 - Touch-friendly interface for creating and managing guest Wi-Fi vouchers.
* [Carlgo11/guest-portal](https://github.com/Carlgo11/guest-portal) ⭐ 13 | 🐛 2 | 🌐 JavaScript | 📅 2024-05-20 - External UniFi guest portal.

## Dream Machine Utilities

* [kchristensen/udm-le](https://github.com/kchristensen/udm-le) ⭐ 774 | 🐛 5 | 🌐 Shell | 📅 2026-05-20 - Let's Encrypt support for Ubiquiti UniFi OS.
* [fabianishere/udm-iptv](https://github.com/fabianishere/udm-iptv) ⭐ 622 | 🐛 25 | 🌐 Shell | 📅 2025-06-22 - Helper tool for configuring routed IPTV on the UniFi Dream Machine (Pro).
* [IngmarStein/unifi-sonos-doc](https://github.com/IngmarStein/unifi-sonos-doc) ⭐ 578 | 🐛 3 | 📅 2025-04-06 - How to configure your UniFi network for Sonos.
* [fabianishere/udm-kernel-tools](https://github.com/fabianishere/udm-kernel-tools) ⭐ 339 | 🐛 10 | 🌐 Shell | 📅 2023-04-02 - Tools for bootstrapping custom kernels on the UniFi Dream Machine.
* [iceteaSA/ucg-max-fan-control](https://github.com/iceteaSA/ucg-max-fan-control) ⭐ 239 | 🐛 0 | 🌐 Shell | 📅 2026-08-09 - UXG-Max/Fibre Dynamic Fan Control.
* [fabianishere/udm-kernel](https://github.com/fabianishere/udm-kernel) ⭐ 135 | 🐛 3 | 🌐 C | 📅 2023-01-24 - Custom Linux kernels for the UniFi Dream Machine.
* [renedis/ubnt-auto-fan-speed](https://github.com/renedis/ubnt-auto-fan-speed) ⭐ 118 | 🐛 2 | 🌐 Shell | 📅 2026-06-22 - Automatic fan speed setting on UDM-PRO 1.8.5+ firmware.
* [davidjenni/udm-pro-network](https://github.com/davidjenni/udm-pro-network) ⭐ 87 | 🐛 2 | 📅 2023-03-11 - UniFi UDM-Pro prosumer network configuration.
* [TobyAnscombe/udm-setup](https://github.com/TobyAnscombe/udm-setup) ⭐ 85 | 🐛 0 | 📅 2026-07-14 - Guide for setting up IoT VLANs on the UniFi Dream Machine.
* [esmith443/Verizon-ONT-Bypass](https://github.com/esmith443/Verizon-ONT-Bypass) ⭐ 80 | 🐛 2 | 📅 2026-07-29 - Guide for bypassing the Verizon FiOS ONT with an Iszo XPON UNO on a UDM Pro.
* [cdchris12/UDM-DNS-Fix](https://github.com/cdchris12/UDM-DNS-Fix) ⭐ 78 | 🐛 3 | 🌐 Python | 📅 2023-05-22 - Script for DHCP hostname resolution on UniFi Dream Machine Pro firmware.
* [blackjid/inadyn-cloudflare](https://github.com/blackjid/inadyn-cloudflare) ⭐ 67 | 🐛 2 | 🌐 JavaScript | 📅 2024-08-28 - Cloudflare Dynamic DNS backend for Inadyn - for use with UniFi Dream Machine / Pro.
* [scyto/multicast-relay](https://github.com/scyto/multicast-relay) ⭐ 62 | 🐛 3 | 🌐 Dockerfile | 📅 2026-08-24 - Multicast-relay Docker for UniFi Dream Machines.
* [dlk3/udm-hacks](https://github.com/dlk3/udm-hacks) ⭐ 31 | 🐛 0 | 🌐 Python | 📅 2024-07-06 - Collection of scripts and tweaks for the UniFi Dream Machine Pro.
* [whi-tw/macvlan-unifios](https://github.com/whi-tw/macvlan-unifios) ⚠️ Archived - Macvlan kernel module for UniFi OS devices.
* [xpherism/udm-proxy](https://github.com/xpherism/udm-proxy) ⭐ 21 | 🐛 0 | 🌐 Shell | 📅 2023-03-04 - Caddy proxy for Ubiquiti UDM Pro.
* [johnstonjs/unifios-utils](https://github.com/johnstonjs/unifios-utils) ⭐ 16 | 🐛 0 | 🌐 Shell | 📅 2026-05-24 - Shell utilities for managing services and configurations on UniFi OS.

## EdgeRouter / EdgeOS

* [britannic/blacklist](https://github.com/britannic/blacklist) ⭐ 536 | 🐛 4 | 🌐 Go | 📅 2023-09-06 - Blacklist and Adware Blocking for the Ubiquiti EdgeMax Router.
* [j-c-m/ubnt-letsencrypt](https://github.com/j-c-m/ubnt-letsencrypt) ⭐ 483 | 🐛 3 | 🌐 Shell | 📅 2023-11-19 - Let's Encrypt setup instructions for Ubiquiti EdgeRouter.
* [sowbug/mkeosimg](https://github.com/sowbug/mkeosimg) ⭐ 201 | 🐛 4 | 🌐 Shell | 📅 2026-07-14 - Make a Ubiquiti EdgeOS image from a system tarball.
* [hungnguyenm/edgemax-acme](https://github.com/hungnguyenm/edgemax-acme) ⭐ 157 | 🐛 5 | 🌐 Shell | 📅 2022-06-17 - Let's Encrypt setup instructions for Ubiquiti EdgeRouter using DNS-01.
* [Genghis1227/guide\_eap\_proxy](https://github.com/Genghis1227/guide_eap_proxy) ⭐ 62 | 🐛 0 | 📅 2021-01-29 - Instructions for AT\&T bypass using EdgeRouter Lite.
* [Matthew1471/EdgeOS-API](https://github.com/Matthew1471/EdgeOS-API) ⭐ 54 | 🐛 1 | 🌐 C# | 📅 2023-01-31 - API wrapper for the Ubiquiti EdgeOS operating system.
* [darkxst/erx-migration](https://github.com/darkxst/erx-migration) ⭐ 50 | 🐛 5 | 🌐 Shell | 📅 2025-04-16 - EdgeRouter X migration scripts for installing or upgrading to OpenWrt.
* [darkgrue/Ubiquiti-DNSCrypt-Proxy-2-Configuration-Scripts](https://github.com/darkgrue/Ubiquiti-DNSCrypt-Proxy-2-Configuration-Scripts) ⭐ 46 | 🐛 0 | 🌐 Shell | 📅 2022-09-03 - Support scripts for DNSCrypt-Proxy 2, dnsmasq, and DNSSEC on EdgeRouter.

## MCP Servers

* [sirkirby/unifi-mcp](https://github.com/sirkirby/unifi-mcp) ⭐ 744 | 🐛 33 | 🌐 Python | 📅 2026-08-25 - MCP server for the UniFi suite including Network, Protect, Access, and Drive.
* [jmasarweh/Unifi-Log-Insights](https://github.com/jmasarweh/Unifi-Log-Insights) ⭐ 264 | 🐛 35 | 🌐 Python | 📅 2026-06-30 - MCP server for querying parsed UniFi firewall logs, threat intelligence, and network analytics.
* [enuno/unifi-mcp-server](https://github.com/enuno/unifi-mcp-server) ⭐ 238 | 🐛 15 | 🌐 Python | 📅 2026-08-19 - MCP server that leverages the official UniFi API.
* [bjeans/homelab-mcp](https://github.com/bjeans/homelab-mcp) ⭐ 40 | 🐛 18 | 🌐 Python | 📅 2026-06-20 - MCP servers for managing homelab infrastructure including UniFi networks.

## Guides & Documentation

* [jeffreykog/unifi-inform-protocol](https://github.com/jeffreykog/unifi-inform-protocol) ⭐ 119 | 🐛 2 | 📅 2020-05-18 - Reverse-engineered documentation of the inform protocol used by UniFi access points.
* [beezly/unifi-apis](https://github.com/beezly/unifi-apis) ⭐ 28 | 🐛 0 | 🌐 Python | 📅 2026-08-20 - UniFi Network and Protect API OpenAPI specifications.
* [MinisculeGirraffe/Tailscale-UDMPro](https://github.com/MinisculeGirraffe/Tailscale-UDMPro) ⭐ 23 | 🐛 2 | 🌐 Shell | 📅 2022-07-23 - Guide to running Tailscale on a UDM(Pro).
* [mzac/unifi-pfsense-tailscale](https://github.com/mzac/unifi-pfsense-tailscale) ⭐ 18 | 🐛 0 | 📅 2026-05-26 - Documentation on how to integrate UniFi with pfSense and Tailscale.
* [ubiquiti-community/unifi-api](https://github.com/ubiquiti-community/unifi-api) ⭐ 13 | 🐛 8 | 🌐 Go | 📅 2026-08-24 - OpenAPI Definition for UniFi Controller API.

***

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## Footnotes

*List curation and project selection by the maintainer. AI tools used for formatting, lint compliance, and alphabetical ordering.*

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-25._
