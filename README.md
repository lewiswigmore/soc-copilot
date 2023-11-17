# [SOC Copilot](https://chat.openai.com/g/g-qvSadylbt-soc-copilot)

In-depth Security Operations assistant. For guidance on usage, ask for `help`.

## Introduction

SOC Copilot is an in-depth Security Operations Center assistant, leveraging the capabilities of OpenAI's custom GPTs feature to deliver targeted support for cybersecurity professionals. This tool provides guidance on various aspects of Security Operations such as threat and vulnerability analysis, risk assessment, remediation strategies and compliance through a keyword-driven interface.

## Features

SOC Copilot now includes a range of tailored capabilities, which are triggered by the following keywords:

- **`analyse`**: Interprets information to outline potential cybersecurity implications.
- **`compliance`**: Offers guidance on standards and regulations compliance pertinent to specific industries.
- **`IoC`**: Explains relevant Indicators of Compromise for threat detection and response, including sourcing a comprehensive list of IoCs from credible online resources.
- **`kql`**: Initiates an 'analyst support mode' for constructing KQL queries tailored for triaging, beginning with a query about the required assistance.
- **`malware`**: Delivers insights into malware families, their TTPs, attack vectors, and includes inquiries about gathering IoCs and devising remediation strategies.
- **`mitre`**: Maps descriptions to specific MITRE ATT&CK stages.
- **`phishing`**: Provides information on common phishing tactics, identification techniques, and mitigation steps. Includes the capability to analyze provided phishing-related data.
- **`risk`**: Identifies and assesses risks associated with the provided information.
- **`spl`**: Assists in constructing SPL (Search Processing Language) queries for data analysis and security investigations, with initial inquiries about the specific assistance needed.
- **`threat actor`**: Collects and presents information about known threat actors, their TTPs, and recent activities.
- **`vulnerability`**: Details known vulnerabilities, their severity, and mitigation strategies.
- **`yara`**: Facilitates the creation of YARA rules based on provided or discovered data.

## Future Features

Ideas to further enhance SOC Copilot include:

- Automated suggestions for hardening configurations based on identified vulnerabilities.
- Third-party risk insights on assessing and mitigating security risks associated with third-party vendors and partners.
- Forensic guidance on digital forensics techniques, tools, and methodologies for investigating security incidents.
- Patch management, including which patches are critical and how to apply them.
- DLP, its importance in preventing data breaches, and strategies for implementing DLP measures.


## Usage

To utilise SOC Copilot, include the relevant keyword in your query. Type `help` to start or see an example below:

- To learn about a specific vulnerability, use: `vulnerability [cve]`. SOC Copilot will gather information, risks and remediation strategies for this vulnerability.
- To collect IoCs for a type of malware, use: `ioc [malware]`. SOC Copilot will provide a list of associated IoCs, like IPs, domains, and file hashes.

## Access

To access SOC Copilot, navigate to the following link: [SOC Copilot on OpenAI](https://chat.openai.com/g/g-qvSadylbt-soc-copilot)

## License

This project is licensed under the OpenAI License for GPT-4 models. Please refer to the [official website](https://openai.com/) for further information. 

## Acknowledgments

- OpenAI and their custom GPTs feature, which empowers users to create specialised tools and assistants.
- Mentioned in the [Awesome-GPT-Agents](https://github.com/fr0gger/Awesome-GPT-Agents) repository by [Thomas Roccia](https://github.com/fr0gger) - A collection of Cyber Security GPT-powered agents, providing insights and inspiration for projects like SOC Copilot.

## DISCLAIMER

A GPT-4 subscription is required to access custom GPTs.