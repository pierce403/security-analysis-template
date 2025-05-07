# Logs Directory

This directory is for storing logs generated during the security analysis.

## Tool Outputs
The output of any automated tools, scanners, or scripts should be saved in this directory. This helps in keeping a record of tool execution and their raw results for later review.

## Agent Log (`agent.log`)
A file named `agent.log` should be maintained within this directory. This log is specifically for tracking actions performed by an AI agent when interacting with or assessing the target system(s).

Each entry in `agent.log` should be appended and follow this format:

```
[YYYY-MM-DD HH:MM:SS] - <Action Description>: <Brief Summary of Result/Observation>
```

**Example:**
```
[2023-10-27 14:35:10] - Performed Nmap scan on 192.168.1.10: Found ports 22, 80, 443 open.
[2023-10-27 14:50:22] - Attempted SQL injection on login page: No vulnerability detected.
```

This log helps in maintaining transparency and an audit trail of the AI agent's activities during the engagement. 