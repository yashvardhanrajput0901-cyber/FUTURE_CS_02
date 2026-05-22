# Email Header Analysis

## Objective

To analyze email headers and identify signs of spoofing or malicious email routing.

---

# Analysis Performed

## SPF Check
Some phishing emails failed SPF validation indicating unauthorized senders.

## DKIM Validation
Missing or invalid DKIM signatures were identified in malicious emails.

## Return-Path Inspection
Return-path addresses differed from displayed sender addresses.

## Originating IP Analysis
Suspicious IP addresses were traced to unknown locations.

---

# Findings

| Indicator | Observation |
|---|---|
| SPF Failure | Detected |
| DKIM Missing | Detected |
| Suspicious Relay | Detected |
| Spoofed Sender | Detected |

---

# Conclusion

Email header analysis revealed multiple indicators of phishing and spoofing attempts.
