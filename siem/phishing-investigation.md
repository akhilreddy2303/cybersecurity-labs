# Phishing Incident Investigation (Simulated)

## Objective
Investigate a suspected phishing email alert triggered in a SIEM environment.

## Tools Used
- Splunk SIEM
- Email header analysis
- Threat intelligence (VirusTotal)

## Scenario
A user reported a suspicious email claiming account compromise and requesting urgent action.

## Investigation Steps
1. Reviewed SIEM alert related to suspicious email activity
2. Analyzed email headers to identify sender IP and domain
3. Checked indicators (IP, URL, hash) against threat intelligence sources
4. Identified phishing characteristics such as spoofed domain and malicious link
5. Escalated the incident and recommended user password reset and awareness action

## Outcome
- Confirmed phishing attempt
- Reduced investigation time through structured analysis
- Improved incident response process and alert handling

## Key Learning
- Importance of correlating SIEM alerts with threat intelligence
- Structured investigation improves SOC efficiency
