# Top 21 Splunk SPL Commands Every SOC Analyst Should Know

## Overview

This project is a practical guide covering **21 essential Splunk Search Processing Language (SPL) commands** commonly used by Security Operations Center (SOC) analysts for log analysis, threat hunting, alert triage, and investigations.

The goal of this project is to demonstrate hands-on knowledge of **Splunk SIEM**, practical query building, and cybersecurity documentation skills.

---

## Project Objectives

- Learn and practice core Splunk SPL commands
- Understand how analysts search and investigate logs
- Perform filtering, aggregation, and visualization
- Build a beginner-friendly SOC reference guide
- Showcase practical cybersecurity skills

---

## Skills Demonstrated

- Splunk Search Processing Language (SPL)
- SIEM Fundamentals
- Log Analysis
- Threat Hunting
- Security Monitoring
- Data Visualization
- Technical Documentation

---

## Commands Covered

1. Index
2. Search Operators
3. Wildcard
4. Pipe Operator
5. Search
6. Fields
7. Dedup
8. Rename
9. Parentheses
10. Quote Operator
11. Table
12. Head
13. Tail
14. Sort
15. Reverse
16. Top
17. Rare
18. Highlight
19. Stats
20. Chart
21. Timechart

---

## Sample SPL Queries

### Search Logs by Index

    index=windowslogs

### Find Specific Events

    index=windowslogs EventID=4103 AccountName=James

### Top Values

    index=windowslogs | top SourceName limit=5

### Count by User

    index=windowslogs | stats count by AccountName

### Time-Based Analysis

    index=windowslogs | timechart count by Image

---

## Files Included

    README.md
    Top_21_Splunk_SPL_Commands.pdf

---

## Why This Project Matters

Understanding SPL is a valuable skill for:

- SOC Analyst Roles
- Security Monitoring
- Incident Response
- Threat Detection
- SIEM Operations
- Blue Team Careers

---

## Future Improvements

- Add advanced SPL detections
- MITRE ATT&CK mapped queries
- PowerShell abuse detections
- Threat hunting scenarios

---

## Author

**Ritik Patel**  
SOC - Threat Research Intern

---
