# Operational Assessments


Operational assessments are vital for evaluating the efficiency, effectiveness, and performance of an organization's operations. By reviewing processes, systems, and procedures, you can identify strengths, weaknesses, opportunities, and threats—helping optimize workflows, improve resource use, and drive continuous improvement.


## Instructions:


1. Choose **one** operational assessment from Chapter 56: *Operational Assessments*, in *The Practice of System and Network Administration*.
1. Complete the assessment, documenting your findings.
1. Submit your completed assessment in the appropriate file format.




### Chapter 56 Sub-Assessments (Options):


1. **Regular Tasks (RT)** – Evaluate routine operational activities and their efficiency.
1. **Emergency Response (ER)** – Assess readiness and processes for handling emergencies.
1. **Monitoring and Metrics (MM)** – Measure how well monitoring systems capture performance and health metrics.
1. **Capacity Planning (CP)** – Examine resource planning to ensure scalability and avoid bottlenecks.
1. **Change Management (CM)** – Review how changes are proposed, tested, approved, and implemented.
1. **New Product Introduction and Removal (NPI/NPR)** – Evaluate processes for deploying or retiring services.
1. **Service Deployment & Decommissioning (SDD)** – Focus on service rollout and retirement mechanisms.
1. **Performance and Efficiency (PE)** – Assess the operational performance and process efficiency.
1. **Service Delivery: The Build Phase** – Look into provisioning, automation, and build procedures.
1. **Service Delivery: The Deployment Phase** – Evaluate deployment practices and repeatability.
1. **Toil Reduction** – Identify repetitive manual work ("toil") and opportunities for automation.
1. **Disaster Preparedness** – Assess preparedness for disasters, including planning and recovery strategies.




### Submission Requirements:


* Select **one** of the operational assessment topics above and use the listed scenario that matches the chosen assessment.
* Produce a **written report** covering:
  * Scope and purpose of the assessment.
  * Methods used (e.g., interviews, logs, metrics, walkthroughs).
  * Findings (strengths, weaknesses, opportunities, threats).
  * Recommendations for improvement.
  * Supporting evidence (diagrams, extracts, charts, screenshots).
* Submit the report in a **clear, structured format**




## Operational Assessment Scenarios


### Regular Tasks (RT)
Your organization’s IT staff rotates through a daily checklist of tasks, such as checking backups, applying system updates, and reviewing monitoring dashboards. Lately, some tasks are being skipped or duplicated, and staff members complain that the list is too long and inconsistent. You’ve been asked to assess whether the current task schedule is efficient and whether automation could help reduce human error.


### Emergency Response (ER)
Last month, a power outage took down two racks of servers in the data center. It took three hours before systems were restored, and users reported significant downtime. Management wants you to review the incident response process: how the outage was detected, how staff were notified, and whether escalation procedures were followed correctly. Your assessment should identify what worked and what failed.


### Monitoring and Metrics (MM)
Your monitoring system (Prometheus/Grafana or Nagios) is producing hundreds of alerts every day. Many of them are false positives, and some critical alerts get buried in the noise. The operations team suspects that thresholds and alerting rules are outdated. You’ve been tasked with reviewing the monitoring system’s configuration and the usefulness of its metrics to improve reliability and reduce alert fatigue.


### Capacity Planning (CP)
The company’s customer-facing web application has grown 30% in users over the past year, and holiday season traffic is expected to double. During peak loads, response times increase significantly. Your task is to review CPU, RAM, disk, and network capacity across servers and cloud services to determine whether the current infrastructure can handle growth. Provide recommendations for scaling.


### Change Management (CM)
Two weeks ago, a database outage occurred after a configuration change was applied without peer review. The change log is incomplete, and rollback steps weren’t documented. Management is asking for an operational assessment of the change management process: how changes are requested, tested, approved, implemented, and tracked.


### New Product Introduction and Removal (NPI/NPR)
The company is rolling out a new cloud-based payroll system while decommissioning the legacy HR server. The IT team has struggled with planning the cutover, and employees report confusion about which system to use. You’ve been assigned to review the introduction and retirement process, ensuring service continuity, communication, and data migration are handled properly.


### Service Deployment & Decommissioning (SDD)
The DevOps team recently deployed a new internal wiki service, but discovered post-deployment that it was missing SSL certificates and user authentication policies. Similarly, old applications remain online months after they’re no longer used. Your assessment should focus on whether deployments and decommissions are standardized, automated, and documented to prevent these oversights.


### Performance and Efficiency (PE)
Employees have complained that the ERP system runs slowly, especially during end-of-month reporting. IT staff suspect the problem is related to database indexing and network bottlenecks. Management has asked you to assess the efficiency of the system’s operations, identify performance bottlenecks, and recommend improvements.


### Service Delivery: The Build Phase


A new ticketing system is being built internally, but developers report the build pipeline is inconsistent—sometimes it fails due to missing dependencies or configuration mismatches. Your assessment should review the build process: version control, CI/CD pipelines, test coverage, and repeatability of the build steps.


### Service Delivery: The Deployment Phase
The organization recently deployed a new CRM application, but deployment took longer than expected, with manual steps that caused delays. Some features were missing in production compared to the test environment. You are tasked with evaluating the deployment phase to determine whether it can be automated, standardized, and improved to reduce risk.


### Toil Reduction
System administrators spend several hours each week resetting user passwords, manually rotating logs, and patching servers. Many of these tasks are repetitive, low-value, and prone to mistakes. You are asked to assess the level of operational “toil” in the environment and recommend opportunities for automation (e.g., self-service password reset, log management tools, patch automation).


### Disaster Preparedness
The company’s data center is in a flood-prone area. Although backups are being performed, it is unclear whether they are restorable, and no recent disaster recovery test has been conducted. Management is requiring a full assessment of disaster preparedness, including data recovery, failover systems, communication plans, and staff readiness.