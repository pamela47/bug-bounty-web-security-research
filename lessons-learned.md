# Lessons Learned
## Session 1 – Aikido Research

During initial bug bounty reconnaissance and application mapping, several key lessons were identified:

### Technical Learning
- Configured Burp Suite with Firefox proxy and HTTPS certificate trust
- Observed HTTP traffic through Burp HTTP history
- Identified API-driven application behaviour
- Performed passive reconnaissance and dashboard mapping

### Security Learning
- Scope and program rules should be reviewed before testing
- Reconnaissance and mapping provide context before validation
- Sensitive values such as cookies and sessions must be redacted before publication
- Business-context understanding helps guide security analysis
## Key Takeaways
- Read scope before testing
- Understand out-of-scope rules
- Map before testing
- Document carefully
- Follow responsible disclosure principles
- Focus on business impact and safe testing
