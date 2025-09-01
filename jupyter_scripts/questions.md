Log Analysis & SQL/Database Queries

You’re given an application log database (like the one you built).
Q: How would you query for server spikes in error rates over the last 24 hours?

Q: How would you detect suspicious login activity (e.g., brute force or impossible travel) using this schema?

Q: How could you join auth_events and request_logs to detect potentially compromised accounts?

Incident Response & Threat Hunting

Q: Walk me through how you would respond if you saw repeated 500 errors from /v1/orders tied to a specific user.

Q: If you notice multiple LOGIN_FAILURE followed by a LOGIN_SUCCESS from the same IP, how would you investigate further?

Q: Describe how you’d determine if a suspicious deployment (deployments table) introduced malicious behavior.

Security Engineering Concepts

Q: Explain the difference between detection engineering and incident response.

Q: How would you design alerting on latency anomalies (e.g., sudden spike to 1500ms in stage API)?

Q: What controls would you add to prevent malicious users from exploiting your API endpoints?

Networking & Infrastructure

Q: How do you differentiate between a DDoS vs. normal traffic surge in logs?

Q: Which fields here (service, env, endpoint, bytes_sent) could help you detect data exfiltration?

Q: If you wanted to block suspicious IPs (203.0.113.11) at the firewall, how would you automate it?


Behavioral / Scenario-Based

Q: Tell me about a time you investigated a log anomaly that turned out to be a real incident.

Q: How do you balance engineering reliability with security monitoring?

Q: If your SIEM rules were noisy, how would you tune them without missing true positives?