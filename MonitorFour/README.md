# MonitorFour – Security Assessment

This folder contains a security assessment for the Hack The Box machine MonitorFour.  
The assessment was done in a controlled lab environment for learning and practice purposes.

---

## Overview

MonitorFour is a Windows system that represents a monitoring or management server.  
The goal of this assessment was to understand how the system could be accessed and what could happen after access was gained.

The focus was not on complex attacks, but on basic security mistakes in system configuration.

---

## Main Findings

- A monitoring service was exposed and could be accessed without proper restrictions.
- The service was running with very high permissions.
- Once access was obtained, full control of the system was immediately available.
- No additional steps were needed to gain higher privileges.

This shows that the system was unsafe due to poor configuration.

---

## Security Impact

With this level of access, an attacker could:

- Control the system
- Read, change, or delete important files
- Turn off security or monitoring features
- Keep long-term access to the system
- Use the system to reach other machines on the same network

Because full access was gained right away, the risk is considered high.

---

## What This Shows

This case shows that:
- Simple configuration mistakes can cause serious security problems
- Services should not run with more permissions than necessary
- Access control is just as important as fixing software bugs

---

## Recommendations

- Limit access to monitoring and management services
- Reduce service permissions to only what is needed
- Regularly review system settings
- Enable logging to detect unusual activity

---

## Notes

- This assessment was performed only in a lab environment.
- Technical attack details are intentionally not included.
- The focus is on understanding the problem and its impact.

For full details, please see the attached security assessment report.
