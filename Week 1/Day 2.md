# A06:2021 – Vulnerable and Outdated Components

## Description:
- Applications using unsupported, outdated, or vulnerable software components may inherit known security flaws.

## Examples:
- Outdated JavaScript libraries.
- Unpatched frameworks with known vulnerabilities.

## Impact:
- Remote code execution
- Data breaches
- System compromise
- A07:2021 – Identification and Authentication Failures

## Description:
- Authentication mechanisms that are poorly implemented can allow attackers to compromise user accounts.

## Examples:
- Weak passwords.
- Missing multi-factor authentication.
- Predictable session identifiers.

## Impact:
- Account takeover
- Unauthorized access
- Privilege escalation
- A08:2021 – Software and Data Integrity Failures

## Description:
- These vulnerabilities occur when software updates, CI/CD pipelines, or application data cannot be trusted.

## Examples:
- Unsigned software updates.
- Insecure deserialization.
- Compromised third-party packages.

## Impact:
- Malware execution
- Supply-chain attacks
- System compromise
- A09:2021 – Security Logging and Monitoring Failures

## Description:
- Insufficient logging and monitoring prevent organizations from detecting and responding to attacks promptly.

## Examples:
- Failed login attempts not logged.
- Missing security alerts.

## Impact:
- Delayed incident response
- Undetected breaches
- Increased damage from attacks
- A10:2021 – Server-Side Request Forgery (SSRF)

## Description:
- SSRF occurs when an application fetches remote resources without validating user-supplied URLs, allowing attackers to access internal systems.

## Examples:
- Accessing internal APIs through a vulnerable web application.
- Cloud metadata service exposure.

## Impact:
- Internal network scanning
- Sensitive information disclosure
- Remote exploitation opportunities
