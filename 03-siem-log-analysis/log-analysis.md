# Log Analysis Findings

## Observation
Multiple endpoints executed PowerShell with encoded commands shortly after opening Word documents.

## Risk Assessment
This behavior strongly correlates with phishing-delivered malware campaigns.

## False Positive Analysis
- Legitimate admin scripts excluded
- Office macro-based execution confirmed

## Recommendation
- Enable PowerShell Script Block Logging
- Alert on Office → PowerShell process chain

