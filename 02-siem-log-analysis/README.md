# 📊 SIEM Log Analysis – E-Commerce Website Outage Investigation

##  Project Overview

This project demonstrates how Security Information and Event Management (SIEM) tools and centralized logging support the detection, investigation, and response to critical business outages.

A simulated e-commerce website became unavailable, disrupting customer access and transactions. The objective was to analyze likely causes using relevant log sources and explain how SOC operations would respond.

---

##  Objectives

* Identify useful log sources during a website outage
* Determine possible root causes
* Explain SIEM correlation capabilities
* Support incident response decision-making
* Reduce downtime and business impact

---

##  Incident Scenario

The organization’s primary e-commerce platform became inaccessible to customers, preventing purchases and affecting business continuity.

Potential causes included:

* Distributed Denial of Service (DDoS)
* Web server failure
* Application crash
* Database outage
* Unauthorized access activity
* DNS or network disruption

---

##  Relevant Log Sources Reviewed

| Log Source       | Purpose                                       |
| ---------------- | --------------------------------------------- |
| Web Server Logs  | HTTP errors, traffic spikes, request patterns |
| Application Logs | Internal failures, code errors                |
| System Logs      | CPU usage, crashes, service restarts          |
| Firewall Logs    | Allowed/blocked traffic, suspicious IPs       |
| IDS/IPS Logs     | Threat signatures, exploit attempts           |
| Database Logs    | Query failures, lock issues                   |
| DNS Logs         | Resolution failures, hijacking indicators     |

---

##  SIEM Capabilities Used

* Centralized log collection
* Real-time alerting
* Event correlation
* Timeline reconstruction
* Threat prioritization
* IOC investigation
* Rapid incident triage

---

##  Business Impact Analysis

Without rapid detection:

* Revenue loss increases
* Customer trust declines
* Operational disruption expands
* Recovery time increases
* Reputational damage worsens

With SIEM visibility:

* Faster Mean Time to Detect (MTTD)
* Faster Mean Time to Respond (MTTR)
* Improved resilience
* Better decision-making

---

##  SOC Response Workflow

1. Receive outage alert
2. Review SIEM dashboard
3. Correlate firewall + server events
4. Identify likely root cause
5. Escalate or contain threat
6. Support restoration efforts
7. Document incident findings

---

##  Skills Demonstrated

* Log Analysis
* SIEM Investigation
* Alert Triage
* Incident Response
* Threat Detection
* Root Cause Analysis
* Business Continuity Awareness

---

##  Conclusion

This project highlights the importance of SIEM platforms and effective monitoring in protecting business operations. Centralized visibility enables SOC analysts to quickly detect incidents, investigate causes, and support timely recovery of critical services.
