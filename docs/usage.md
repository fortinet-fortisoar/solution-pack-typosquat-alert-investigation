| [Home](../README.md) |
|----------------------|

# Usage

Refer to [Simulate Scenario documentation](https://github.com/fortinet-fortisoar/solution-pack-soc-simulator/blob/develop/docs/usage.md) to understand how to simulate and reset scenarios.

To understand the process FortiSOAR follows to respond to alerts related to typo squatted domains, we have included a scenario &mdash; **Typo Squatting Domain Detected** &mdash; with this solution pack.

## Scenario &mdash; Typo Squatting Domain Detected

This scenario generates an example alert of Type *Phishing* in FortiSOAR's **Alerts** module.

Navigate to the demo alert and note the following:

- The demo alert created is an example of Typo Squat Alert Investigation detecting a typo domain that is *Highly Suspicious*
- The alert is of type *Phishing*
- The reported alert contains the following information:
    - Typo Domain Details:
        - Typo Domain
        - Original Domain
        - Severity Score
        - Status
    - Source
    - Source ID
    - Source IP
    - Indicators are created for monitored domain, typo domain and Source IP Address

- The response playbook `Investigate High Risk Typo Squatting Domain Response` runs by selecting the Typo Squat alert record. Below are the *flowchart* of the this playbook

    ![Typo Domain Alert](./res/Typo%20Squat%20Domain.png)

| [Installation](./docs/setup.md#installation) | [Configuration](./docs/setup.md#configuration) | [Contents](./docs/contents.md) |
|--------------------------------------------|----------------------------------------------|------------------------|