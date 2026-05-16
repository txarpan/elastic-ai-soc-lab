# Elastic AI SOC Lab

An elite SOC detection and AI-powered triage lab built on Elastic Stack 8.x with autonomous alert investigation using Claude API, VirusTotal, and AbuseIPDB.

## Stack
- Elasticsearch 8.19.15 + Kibana (Fedora host)
- Elastic Agent (Fedora + Ubuntu + Windows endpoints)
- Python AI Triage Agent
- Claude API (reasoning engine)
- VirusTotal + AbuseIPDB (threat intel)

## Detection Coverage
- 5 custom detection rules mapped to MITRE ATT&CK
- 5 case studies (CS-001 to CS-005)
- Automated IR report generation
- Auto-blocking via UFW

## Author
Arpan Mukherjee
