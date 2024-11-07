# Internet-Wide-ICS-Scanning
This is a scientific research project to explore the configuration of security settings for mainstream programmable controllers (PLCs) in IPV4 cyberspace.
We collect information based on databases from Shodan, Censys, Binaryedge and Fofa and interact with PLCs in the IPV4 to obtain the status of their security settings.
According to our findings, 93.32% of the PLCs have insecure settings and the major manufacturers and models are listed below:

Schneider: M221, M340, M580
Rockwell: 1400, 1100
Siemens: S7-300

We recommend that PLC users follow the following guideline to configure PLCs exposed to cyberspace:
Guideline-1: Keep the PLC in ''Run'' mode. 
Guideline-2: Keep the PLC in ''Local'' mode.
Guideline-3: Enable access authentication.
Guideline-4: Enable both read and write authentication.

We will gradually disclose details of our research in the future.

If you have a PLC connected to the IPV4 cyberspace and would like to avoid being scanned by us, please contact us.
