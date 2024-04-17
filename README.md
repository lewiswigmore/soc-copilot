# [SOC Copilot](https://chat.openai.com/g/g-qvSadylbt-soc-copilot)

In-depth Security Operations assistant. For guidance on usage, ask for `help`. NOTICE: WIP migrating to Azure OpenAI Deployment 

## Introduction

SOC Copilot is an in-depth Security Operations Center assistant, leveraging the capabilities of OpenAI's custom GPTs feature to deliver targeted support for cybersecurity professionals. This tool provides guidance on various aspects of Security Operations such as threat and vulnerability analysis, risk assessment, remediation strategies and compliance through a keyword-driven interface.

## Features

SOC Copilot now includes a range of tailored capabilities, which are triggered by the following keywords:

- **`analyse`**: Activates SOC Copilot's ability to interpret provided information and explain potential cybersecurity implications.
- **`compliance`**: Engages SOC Copilot in providing guidance on compliance with standards and regulations relevant to the user's industry, requesting additional context if necessary.
- **`forensics`**: Initiates support for digital forensic analysis, including data acquisition, preservation, analysis, and reporting processes.
- **`IoC`**: Commands SOC Copilot to explain relevant Indicators of Compromise for threat detection and response, including sourcing a list of IoCs such as IPs, C2 servers, domains, URLs, and file hashes from reputable online sources.
- **`kql`**: Triggers assistance in constructing KQL queries for triaging, use-case management, or tuning existing rule logic, with initial queries about the needed KQL assistance.
- **`malware`**: Prompts explanations about malware families, their TTPs, attack vectors, and inquires about IoCs gathering and remediation strategies.
- **`mitre`**: Directs SOC Copilot to map information to specific MITRE ATT&CK stages.
- **`patch`**: Provides assistance with patching vulnerabilities, recommending information sourced from official and credible vendor sources online.
- **`phishing`**: Offers details about common phishing tactics, recognition techniques, and mitigation steps, and can analyze provided phishing-related data.
- **`risk`**: Identifies risks associated with the given information, potentially requesting additional environmental context for elaboration.
- **`spl`**: Assists in constructing SPL (Search Processing Language) queries for data analysis, security investigations, and use-case management, inquiring specifically about the SPL assistance needed.
- **`threat actor`**: Gathers information about known threat actors, their TTPs, and recent activities.
- **`vulnerability`**: Provides details on known vulnerabilities, their severity, and mitigation strategies, and can also search the internet for information if no specific vulnerability is known. This can be triggered by the `cve` keyword as well.
- **`yara`**: Facilitates the creation of YARA rules based on provided or discovered data.

## Future Features

Ideas to further enhance SOC Copilot include:

- Automated suggestions for hardening configurations based on identified vulnerabilities.
- Third-party risk insights on assessing and mitigating security risks associated with third-party vendors and partners.
- DLP, its importance in preventing data breaches, and strategies for implementing DLP measures.
- Crisis management, support in managing and communicating during a cybersecurity crisis.
- Incident response step-by-step guidance for IR procedures, including initial assessment, containment strategies, eradication techniques, and recovery plans.

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
