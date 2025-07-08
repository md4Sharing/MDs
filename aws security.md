| Service | Primary Purpose | Key Features | Typical Use Cases |
| :-- | :-- | :-- | :-- |
| CloudWatch | Monitoring and observability | Metrics, logs, alarms, dashboards, event monitoring | Resource monitoring, alerting, operational health |
| CloudTrail | Governance, compliance, and audit logging | Records AWS API calls, delivers logs to S3, integrates with CloudWatch Logs | Security auditing, troubleshooting, compliance |
| Config | Resource configuration tracking and compliance | Tracks configuration changes, compliance rules, historical configuration snapshots | Change tracking, compliance auditing |
| Inspector | Automated security assessment and vulnerability management | Scans EC2, ECR, Lambda for vulnerabilities, CIS benchmarks, continuous assessments | Vulnerability management, compliance checks |
| WAF | Web application firewall | Protects against common web exploits, custom rules, managed rule groups | Web app protection, OWASP Top 10 mitigation |
| Shield | DDoS protection | Automatic detection and mitigation, advanced support (Shield Advanced) | DDoS mitigation for web apps and services |
| Security Hub | Security posture management and findings aggregation | Aggregates findings from AWS and third parties, compliance checks, dashboard | Centralized security monitoring, CSPM |
| Trusted Advisor | Resource optimization and best practice checks | Recommendations for cost, security, performance, limits, resilience | Cost optimization, security posture, best practices |
| Audit Manager | Automated evidence collection for audits and compliance | Maps controls to frameworks, collects evidence, generates audit-ready reports | Compliance reporting, audit preparation |
| GuardDuty | Threat detection and continuous security monitoring | Analyzes VPC flow logs, DNS logs, CloudTrail, detects threats, integrates with Security Hub | Threat detection, incident response |

**Notes:**

- CloudWatch focuses on metrics, logs, and operational visibility
- CloudTrail provides a history of API calls for auditing and security investigations
- Config tracks resource configurations and compliance over time
- Inspector automates vulnerability assessments for workloads and containers
- WAF protects web applications from common attacks and bots
- Shield provides DDoS protection, with advanced options for large-scale attacks
- Security Hub centralizes security findings and checks compliance frameworks
- Trusted Advisor offers best practice recommendations across cost, security, and performance
- Audit Manager automates evidence collection for compliance audits
- GuardDuty delivers threat detection using machine learning and log analysis
