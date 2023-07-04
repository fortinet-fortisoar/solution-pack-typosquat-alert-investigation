| [Home](../README.md) |
|----------------------|

# Installation

1. To install a solution pack, click **Content Hub** > **Discover**.   
2. From the list of solution pack that appears, search for and select **Typosquat Alert Investigation**.    
3. Click the **Typosquat Alert Investigation** solution pack card.   
4. Click the **Install** button on the bottom to begin the installation.

## Prerequisites

The **Typosquat Alert Investigation** solution pack depends on the following solution packs that are installed automatically &ndash; if not already installed.

| Solution Pack Name | Version          | Purpose                                                  |
|:-------------------|:-----------------|:---------------------------------------------------------|
| SOAR Framework     | v2.1.0 and later | Required for Incident Response modules                   |
| SOC Simulator      | v1.0.2 and later | Required for Scenario Module and SOC Simulator connector |

# Configuration

For optimal performance of the **Typosquat Alert Investigation** solution pack, you must configure:

- **Fortinet FortiRecon Brand Protection** connectors to get high risk typo domain alerts. 
    - To configure and use the *Fortinet FortiRecon Brand Protection* connector, refer to [*Fortinet FortiRecon Brand Protection Documentation*](https://docs.fortinet.com/document/fortisoar/1.0.0/fortinet-fortirecon-brand-protection/475/fortinet-fortirecon-brand-protection-v1-0-0)
- **Whois Freaks** connectors to get DNS lookup and whois information of Domain. 
    - To configure and use the *Whois Freaks* connector, refer to [*Whois Freaks Documentation*](https://docs.fortinet.com/document/fortisoar/1.0.0/whois-freaks/475/whois-freaks-v1-0-0)
- **Whois XML API** connectors to get Domain and Sub-Domain information. 
    - To configure and use the *Whois XML API* connector, refer to [*Whois XML API Documentation*](https://docs.fortinet.com/document/fortisoar/1.0.0/whois-xml-api/475/whois-xml-api-v1-0-0)
- **Censys** connectors to get domain certificate. 
    - To configure and use the *Censys* connector, refer to [*Censys Documentation*](https://docs.fortinet.com/document/fortisoar/1.0.0/censys/475/censys-v1-0-0)
- **URLScan.io** connectors to get domain certificate. 
    - To configure and use the *URLScan.io* connector, refer to [*URLScan.io Documentation*](https://docs.fortinet.com/document/fortisoar/1.1.2/urlscan-io/440/urlscan-io-v1-1-2)

| [Usage](./docs/usage.md) | [Contents](./docs/contents.md) |
|--------------------------------------------|----------------------------------------------|