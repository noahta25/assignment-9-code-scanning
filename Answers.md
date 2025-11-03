# Answers to Part 3

Add your answers to the questions in Part 3, Step 2 below. 

## Vulernability Remediation:
### Vulnerability 1: 
1. Which package or library are you addressing?

**I am addressing a vulnerability in the python-cryptography package version 39.0.1 (from the trivy results).**

2. Which CVE is linked to this vulnerability?

**CVE-2023-50782 is linked to this vulnerability. In this vulnerability, an issue was discovered that allows remote attackers to decrypt messages in TLS servers that use RSA key exchanges.**

3. What remediation steps do you suggest?

**The simple remdiation in this instance is to update the package to its latest version (42.0.0).**

### Vulnerability 2:
1. Which vulnerability are you addressing?

**I am addressing a vulnerability in the sqlparse Python library (from the trivy results).**

2. Which CVE is linked to this vulnerability?

**CVE-2024-4340 is linked to this vulnerability. In this vulnerability, if an attacker is able to pass a large nested list using the sqlparse.parse() function, it can lead to Denial of Service.**

3. What remediation steps do you suggest? 

**To remediate this issue, I would suggest identifying which components are utilizing an older version of sqlparse and upgrading them all to the latest version (0.5.0).Additionally, restricting users ability to supply nested queries as well as enabling logging helps to prevent damages in the event that immediate upgrading isn't possible.**