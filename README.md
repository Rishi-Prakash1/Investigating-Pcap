# Threat Intelligence – Malicious PCAP Investigation

## Overview
In this practical exercise, participants will act as threat intelligence investigators and analyse a PCAP file containing suspicious network communication associated with the download of a malicious ZIP archive.

PCAP file: https://drive.google.com/file/d/189WW4hp3I5gwuw8-4PNKbYf0ovc_hOIw/view?usp=sharing

## Objective
Identify the malicious domain, investigate the download activity, recover the downloaded archive, inspect its contents, and use VirusTotal to gather additional malware intelligence.

## Tasks
- Analyse network traffic using Wireshark.
- Identify the malicious domain and hosting server.
- Trace and recover the downloaded ZIP archive.
- Identify the file contained within the archive.
- Investigate the extracted file using VirusTotal.
- Identify malware classification, first-seen timestamp, contacted URLs, and dropped files.

## Expected Outcome
Participants should be able to reconstruct the malicious download activity, identify relevant Indicators of Compromise (IoCs), and prepare an evidence-based threat intelligence report.

**Tools Required:** Wireshark, VirusTotal, and a controlled analysis environment.

**Note:** Do not execute the recovered file on a production system. Perform all analysis in an isolated environment.
