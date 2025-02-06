# Cybersecurity Incident Report: 

# Network Traffic Analysis

| Part 1: Provide a summary of the problem found in the DNS and ICMP  traffic log.  |  |
| :---- | ----- |
| The UDP protocol reveals that: QIN is wrong   This is based on the results of the network analysis, which show that the ICMP echo reply returned the error message: udp port 53 unreachable  The port noted in the error message is used for: 53  The most likely issue is: DNS is down or has been saturated with requests  |  |
|  |  |

| Part 2: Explain your analysis of the data and provide at least one cause of the incident. |
| :---- |
| Time incident occurred: 7pm  Explain how the IT team became aware of the incident: Several customers of clients reported that they were not able to access the client company website www.yummyrecipesforme.com, and saw the error “destination port unreachable” after waiting for the page to load.   Explain the actions taken by the IT department to investigate the incident: Pulled Sample Log Data, analyzing the data and determining cause  Note key findings of the IT department's investigation (i.e., details related to the port affected, DNS server, etc.):   Note a likely cause of the incident: DNS is down or has been saturated with requests |

