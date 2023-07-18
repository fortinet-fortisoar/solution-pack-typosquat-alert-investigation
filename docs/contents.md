| [Home](../README.md) |
|----------------------|

# Contents

The **Typosquat Alert Investigation** solution pack contains the following resources:

## Connectors

| Connector Name                       | Description                                                                                                                                                                                |
|:-------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Fortinet FortiRecon Brand Protection | FortiRecon is a Digital Risk Protection Service (DRPS) product that provides an outside-the-network view to the risks posed to your enterprise.                                            |
| Whois XML API                        | Whois XML API provides comprehensive set of real-time and historic Whois, Domain name and DNS Data                                                                                         |
| Censys                               | Helps fetch information from the Censys search engine                                                                                                                                      |
| URLScan.io                           | URLScan.io provides a service that analyzes websites and the resources they request. URLScan.io provides actions like search domain, ip, hash scan URL and retrieve report of scanned url. |
| WhoisFreaks                          | WhoisFreaks provides well-parsed and structured domain WHOIS data for all domain names, registrars, countries, and TLDs since the birth of internet.                                        |

## Record Sets
| Scenario                       | Description                                                                                                                   |
|:-------------------------------|:------------------------------------------------------------------------------------------------------------------------------|
| Typo Squatting Domain Detected | Demonstrates the scenario where Typosquat Alert Investigation detects a typo squatted domain whose severity score is **High** |

## Playbook Collection

|02 - Use Case - Typosquat Alert Investigation |
|:---------------------------------------------|


| Playbook Name                                                                | Description                                                                                                                                     |
|:-----------------------------------------------------------------------------|:------------------------------------------------------------------------------------------------------------------------------------------------|
| Scenario - Fetch Typo Squatting Domain                                       | Fetches the list of high-severity typo squatted domains discovered by FortiRecon for a specified organization and creates alerts for the same |
| Scenario - Fetch Typo Squatting Domain > Create Alerts and Indicators Domain | Create Alerts and Indicators of Typo Squatting                                                                                                  |
| Investigate High Risk Typo Squatting Domain Response                         | Investigate High Risk Typo Squatting Domain Response                                                                                            |


>**Warning:** We recommend you clone these playbooks before customizing to avoid information loss while upgrading the solution pack.

| [Installation](./setup.md#installation) | [Configuration](./setup.md#configuration) | [Usage](./usage.md) |
|-----------------------------------------|-------------------------------------------|---------------------|