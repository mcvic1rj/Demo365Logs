# REN-ISAC Disclaimer
Version 2.1 (September 2009)
## 1.0 Disclaimer
1.1 Information is shared within REN-ISAC for the objective of cyber security protection and
response. Information is shared in good faith and there are no explicit or implied guarantees or
warranties to the veracity or applicability of the information.

1.2 Information received from any REN-ISAC service, product, or member must be analyzed fully by
representatives of the receiving institution, and inherent risks determined and understood. Any local
action taken must be informed by local technical expertise and applied as appropriate to the local
technical, functional, and cultural environments.

1.3 The REN-ISAC, its sponsoring organizations, and members accept no responsibility for negative
impacts of any sort that results from local actions taken on information sent to the membership
generally, or to specific institutions.


## Script samples
## Gather Message Trace Logs

### What this script does

This script will collect message trace logs from Office 365 to be ingested into a SIEM.

### What information is collected

Message Metadata from Message trace logs:
* Sending IP address
* from address
* recipient address
* subject
* size
* Message ID
* status
* recieved date

### How is it exported

This script will export the logs under the `/json/` directory.

### What do I do with this data

Use this data to enrich incident response activies, set threshold alerts for emails, ect.

### Known issues
* This information can be slow to collect, so it is not the best for rapid investigation.