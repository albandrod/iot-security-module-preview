# IoT Security Module - Azure RTOS (Preview)

Azure Security Center for IoT security module provides a comprehensive security solution for Azure RTOS devices. Azure RTOS is shipped with a built-in security module that covers common threats on real-time operating system devices.

Azure Security Center for IoT security module with Azure RTOS support offers the following features:
- Detection of malicious network activities: Every device inbound and outbound network activity is monitored (supported protocols: TCP, UDP, ICMP on IPv4 and IPv6). Azure Security Center for IoT inspects each of these network activities against the Microsoft Threat Intelligence feed. The feed gets updated in real-time with millions of unique threat indicators collected worldwide.
- Device behavior baselining based on custom alerts: Allows for clustering of devices into security groups and defining the expected behavior of each group. As IoT devices are typically designed to operate in well-defined and limited scenarios, it is easy to create a baseline that defines their expected behavior using a set of parameters. Any deviation from the baseline, triggers an alert.
- Improve the security hygiene of the device: By leveraging the recommended infrastructure Azure Security Center for IoT provides, gain knowledge and insights about issues in your environment that impact and damage the security posture of your devices. Poor IoT device security posture can allow potential attacks to succeed if left unchanged, as security is always measured by the weakest link within any organization.

![Monitoring Capabilities](img/asc_for_iot_monitoring_capabilities.png)

Azure Security Center for IoT security module for Azure RTOS is provided as a free download for your devices. The Azure Security Center for IoT cloud service is available with a 30 day trial per Azure subscription. Download the Azure Security Center for IoT security module for Azure RTOS today to get started.

For more information about Azure Security Center for IoT, please refer to this [link](https://docs.microsoft.com/en-us/azure/asc-for-iot/).

---

## Getting Started With IoT Security Module Guides

The following board specific guides will get you started with Azure RTOS and IoT Security Module:

> * Getting started with the NXP [MIMXRT1060-EVK](NXP/MIMXRT1060-EVK)

## Reporting Security Vulnerabilities

If you believe you have found a security vulnerability in any Microsoft-owned repository that meets Microsoft's Microsoft's definition of a security vulnerability, please report it to the [Microsoft Security Response Center](SECURITY.md).

## Contribution, feedback and issues
If you encounter any bugs, have suggestions for new features or if you would like to become an active contributor to this project please follow the instructions provided in the contribution guideline for the corresponding repo.
For general support, please post a question to [Stack Overflow](http://stackoverflow.com/questions/tagged/azure-rtos) using the `azure-rtos` tags.