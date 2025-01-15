# SCOMCoreAddendum - Proactive.Microsoft.System.Center.Core.Monitoring.Addendum v1.0.2.3

Download [here](https://github.com/theKevinJustin/SCOMCoreAddendum/blob/main/Microsoft.Windows.Server.DNS.Monitoring.Addendum.xml)

### Proactive.Microsoft.System.Center.Core.Monitoring.Addendum.xml
Proactive.Microsoft.System.Center.Core.Monitoring.Addendum - Management pack provides multiple overrides, dialy reports, alert closure, DWDataRP integration rule/monitor to point out SCOM DW size and storage issues.  Creates a High agent handle count with definable RegEx.

#### Additional capabilities include:
DWDataRP workflows for rules/monitors to alert when Perf,State,Alerts, etc are taking too much of the SCOM datawarehouse.
Overrides common alert noise from SCOM core pack.


Blog [https://kevinjustin.com/blog/2023/08/30/scomcore-addendum-pack](https://kevinjustin.com/blog/2023/08/30/scomcore-addendum-pack/)](https://kevinjustin.com/blog/2023/08/30/scomcore-addendum-pack/)

# Version History:
```
v1.0.2.3  19 Nov 2024 DWDataRP, Report and Close report changes
v1.0.2.2  18 Oct 2024 Renumber events.  Updated overrides, DWDataRP executable rule/monitor DS with overrides, disabled event collection
v1.0.1.8  21 Dec 2023 Updated Monitor/Rule closure logic, whitespace audit
v1.0.1.6  18 Jul 2023 Added override to pack
v1.0.1.5  27 Jun 2023 Reports updated to informational, Event collection rule added
v1.0.1.4   7 Feb 2023 Updated with cleanup with Remaining and other alert breakdowns
v1.0.1.3  23 Jan 2023 Updated with MP methods, updated DS/WA reports
v1.0.1.2   5 Jan 2023 Event collection disabled
v1.0.0.9  21 Apr 2022 Updated Core Monitoring for handle alerts
v1.0.0.6   8 Feb 2022 Added 'Management Configuration Service group' alert
v1.0.0.5  10 Dec 2021 Updated ft to select, re-wrote report for agent threshold, paging, and other errors
v1.0.0.1   4 May 2021 Updated DS and WA with additional logging, build report first, then cleanup
v1.0.0.0   6 Apr 2021 Created management pack for SCOM Core mgmt pack auto closure cleanup
