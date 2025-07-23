<p align="center">
    <a href="#readme">
        <img alt="ANY.RUN logo" src="https://raw.githubusercontent.com/anyrun/anyrun-sdk/b3dfde1d3aa018d0a1c3b5d0fa8aaa652e80d883/static/logo.svg">
    </a>
</p>

______________________________________________________________________

# ANY.RUN connectors for OpenCTI

This repository provides integrations of the OpenCTI threat intelligence platform with three key components: the ANY.RUN interactive sandbox, Threat Intelligence (TI) lookups, and structured TI feeds. The centerpiece is the ANY.RUN integration, which enables automated submission of files and URLs from OpenCTI for dynamic malware analysis. It retrieves detailed sandbox reports—including network activity, dropped files, and MITRE ATT&CK techniques—that enrich observables in OpenCTI. These insights help analysts rapidly assess threats and correlate malicious behaviors across incidents.   
The TI lookup module allows querying external sources for additional context on indicators of compromise (IOCs), while the TI feeds module supports scheduled ingestion of threat data from trusted providers. Together, these integrations extend OpenCTI’s analytical and data enrichment capabilities.  
The connectors are Docker-ready, API-driven, and easy to configure. By combining real-time sandbox intelligence with external data sources, this solution strengthens threat detection, investigation, and response workflows within the OpenCTI environment.  

For more detailed information, please use the README files in the subfolders.
