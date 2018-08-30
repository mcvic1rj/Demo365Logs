# Gather Message Trace Logs

## What this script does

This script will collect message trace logs from Office 365 to be ingested into a SIEM.

## What information is collected

Message Metadata from Message trace logs:
* Sending IP address
* from address
* recipient address
* subject
* size
* Message ID
* status
* recieved date

## How is it exported

This script will export the logs under the `/json/` directory.

## What do I do with this data

Use this data to enrich incident response activies, set threshold alerts for emails, ect.

## Known issues
* This information can be slow to collect, so it is not the best for rapid investigation.