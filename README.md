<p align="center">
    <a href="#readme">
        <img alt="ANY.RUN logo" src="https://raw.githubusercontent.com/anyrun/anyrun-sdk/b3dfde1d3aa018d0a1c3b5d0fa8aaa652e80d883/static/logo.svg">
    </a>
</p>

______________________________________________________________________

# ANY.RUN connectors for OpenCTI 

This repository provides integrations of the OpenCTI threat intelligence platform with [ANY.RUN](https://any.run/?utm_source=anyrungithub&utm_medium=documentation&utm_campaign=opencti_main&utm_content=linktolanding)'s services:  

* [Interactive Sandbox](https://any.run/features/?utm_source=anyrungithub&utm_medium=documentation&utm_campaign=opencti_main&utm_content=linktosandboxlanding)
* [Threat Intelligence Lookup](https://any.run/threat-intelligence-lookup/?utm_source=anyrungithub&utm_medium=documentation&utm_campaign=opencti_main&utm_term=310725&utm_content=linktolookuplanding) 
* [Threat Intelligence Feeds](https://any.run/threat-intelligence-feeds/?utm_source=anyrungithub&utm_medium=documentation&utm_campaign=opencti_main&utm_term=310725&utm_content=linktofeedslanding) 

The connectors are Docker-ready, API-driven, and easy to configure. By combining real-time sandbox intelligence with external data sources, this solution strengthens threat detection, investigation, and response workflows within the OpenCTI environment. 

## Connector capabilities 

### Interactive Sandbox: Early detection of evasive threats 

The connector for the Interactive Sandbox enables automated submission of files and URLs from OpenCTI for dynamic malware analysis. It retrieves detailed sandbox reports—including network activity, dropped files, and MITRE ATT&CK techniques—that enrich observables in OpenCTI.
These insights help analysts rapidly assess threats and improve the incident detection rate to minimize response delays and breach risks. 

[See documentation](https://github.com/anyrun/anyrun-integration-opencti/tree/main/anyrun-integration-sandbox)

### Threat Intelligence Lookup: Faster triage, informed response, and proactive hunting 

The connector for Threat Intelligence Lookup  allows for enriching OpenCTI artifacts with context from live attack data from over 15K SOCs. It shortens investigation time by providing rapid insights into malicious URLs, IPs, domains, and hashes.
This critical context helps security teams streamline triage, cut MTTD, improve incident response, and identify hidden malware in high alert volume environments. 

[See documentation](https://github.com/anyrun/anyrun-integration-opencti/tree/main/anyrun-integration-ti-lookup)

### Threat Intelligence Feeds: Fresh malicious indicators for expanded threat coverage

The connector for Threat Intelligence Feeds supports ingestion of high-fidelity indicators of compromise (IPs, domains, URLs), extracted directly from real-time detonations of the latest threats inside ANY.RUN’s Interactive Sandbox. TI Feeds continuously supply fresh IOCs every two hours, ensuring SOC teams receive actionable intelligence on attacks still active in the wild.
This enables SOCs to monitor emerging threats and update defenses proactively, minimizing the risk of undetected attacks. 

[See documentation](https://github.com/anyrun/anyrun-integration-opencti/tree/main/anyrun-integration-ti-feed)

### Request support or access to ANY.RUN’s products 

Feel free to reach out to us for help with integration, a quote, or demo via the [contact us form](https://app.any.run/contact-us/?utm_source=anyrungithub&utm_medium=documentation&utm_campaign=opencti_main&utm_content=linktocontactus). 