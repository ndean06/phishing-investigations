# Phishing Investigation  Uber Brand Impersonation

## Summary
- Investigated a phishing email impersonating Uber partnerships
- Confirmed malicious via lookalike domain and WHOIS analysis
- No payload observed; pretexting-style phishing

## Key Indicators
- Lookalike domain: partners-uber[.]com
- Recently registered domain
- Registrar suspension (clientHold)
- Generic partnership lure

## Final Verdict
**Confirmed Phishing – Brand Impersonation**  
MITRE ATT&CK: T1566

## Investigation Report
- 📄 [SOC Investigation Report](report.pdf)

## Confidence & Limitations
This assessment is based on available email content and WHOIS data. Full email headers and user interaction telemetry were not available; therefore, while the activity is confidently classified as phishing via brand impersonation, follow-on activity cannot be confirmed.

## Analyst Actions
- Blocked domain at email gateway
- Performed email trace
- Added IOCs to tracking
- Monitored for follow-up attempts
