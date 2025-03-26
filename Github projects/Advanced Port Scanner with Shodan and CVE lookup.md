# Advanced Port Scanner with Shodan and CVE Lookup 🚀
This is an advanced asynchronous port scanner written in Python. It scans a target for open ports, retrieves banners, identifies services and versions, and performs CVE lookups using the NVD API. Additionally, it can integrate with Shodan to provide extra host details.

## Features
- **Fast asynchronous scanning**: Leverages asyncio for concurrent port scanning.
- **Banner grabbing**: Retrieves banners from open ports for service identification.
- **Service detection**: Identifies services (e.g., Apache, SSH, nginx) along with their versions.
- **CVE lookup integration**: Queries the NVD API for known vulnerabilities based on the service and version.
- **Optional Shodan integration**: Retrieves additional host data from Shodan.
- **Report generation**: Produces reports in both JSON and HTML formats.

**Link to Github repo**: [https://github.com/chrispl89/port_scanner/](https://github.com/chrispl89/port_scanner/)
