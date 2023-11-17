# [SOC Copilot](https://chat.openai.com/g/g-qvSadylbt-soc-copilot)

In-depth Security Operations assistant. For guidance on usage, ask for `help`.

## Introduction

SOC Copilot is an in-depth Security Operations Center assistant, leveraging the capabilities of OpenAI's custom GPTs feature to deliver targeted support for cybersecurity professionals. This tool provides guidance on various aspects of Security Operations such as threat and vulnerability analysis, risk assessment, remediation strategies and compliance through a keyword-driven interface.

## Features

SOC Copilot supports a range of functionalities, which are triggered by the following keywords:

- **'analyse'**: Engages SOC Copilot to interpret the provided information and elucidate potential cybersecurity implications.
- **'compliance'**: Invoking this keyword garners guidance on standards and regulations compliance relevant to the user's industry.
- **'IoC'**: Mentioning 'IoC' commands the system to expound on pertinent Indicators of Compromise and their application in threat detection and response. The assistant will also source a comprehensive list of IoCs, including IPs, C2 servers, domains, URLs, and file hashes from reputable online sources.
- **'kql'**: Utilizing 'kql' activates an 'analyst support mode' for crafting KQL queries tailored for triaging. The Copilot initially queries about the needed KQL assistance.
- **'malware'**: Triggering this keyword enables SOC Copilot to detail malware families, their TTPs, attack vectors, and assists in IoCs collection and remediation strategies. Further inquiry about the host, environment, and scope is conducted if remediation is sought.
- **'mitre'**: When fed with a description, the system maps the input to a specific MITRE ATT&CK stage.
- **'phishing'**: Offers insights into common phishing strategies, recognition of phishing attempts, and mitigation measures. If presented with potential phishing data, SOC Copilot will analyze it for validation.
- **'risk'**: Activating this keyword prompts SOC Copilot to identify and assess risks associated with the provided information.
- **'spl'**: This keyword initiates an 'analyst support mode' for constructing SPL (Search Processing Language) queries, aiding in data analysis and security investigations. The system first inquires about the specific SPL support required.
- **'threat actor'**: Using this keyword signals the Copilot to gather information about known threat actors, their TTPs, and recent activities.
- **'vulnerability'**: This command elicits details on known vulnerabilities, their severity, and proposed mitigation strategies.
- **'yara'**: Employing 'yara' prompts the creation of YARA rules based on the provided or discovered data.

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