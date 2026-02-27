# Meeting Minutes: Vulnerability Management Policy Buy-In
    
    **Date:** February 24, 2026  
    **Attendees:** * **Security Analyst:** Anthony De Leon  
    * **Server Team Lead:** John Doe  
    * **IT Manager:** Jane Smith
    
    ## Agenda
    1. Present the draft Vulnerability Management Policy.
    2. Discuss and finalize Remediation SLAs (Service Level Agreements).
    3. Establish Rules of Engagement for network scanning.
    
    ## Key Discussion Points
    * **SLA Concerns:** The Server Team expressed that a 48-hour patching window for "Critical" vulnerabilities was too aggressive for their current testing workflow. 
    * **Performance Impact:** Concerns were raised regarding Nessus scans causing high CPU utilization on legacy servers during business hours.
    
    ## Decisions Made
    * **Negotiated SLA:** Agreed to move the "Critical" remediation window to **7 days** to allow for stability testing in the dev environment.
    * **Scan Schedule:** All authenticated scans will be scheduled between **18:00 and 06:00** to minimize business disruption.
    
    ## Action Items
    * **Anthony De Leon**: Update the formal Policy Draft with the 7-day SLA.
    * **Server Team**: Provide local admin credentials for the `win-ant-server` asset.
