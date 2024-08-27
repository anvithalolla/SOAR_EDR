# SOAR EDR Integration Project: Automated Detection and Response for Credential Access Attacks

## Project Overview
This project showcases the integration of SOAR (Security Orchestration, Automation, and Response) with EDR (Endpoint Detection and Response) tools to automate the detection and response to credential access attacks. By leveraging LimaCharlie as the EDR solution and Tines as the SOAR platform, the project creates an automated workflow to handle malware infections, specifically focusing on the LaZagne credential retrieval tool.

## Objectives
- **Environment Setup**: Install and configure Windows Server 2022 as the client machine.
- **Facilitate Infection**: Allow LaZagne malware installation by disabling the Windows Server firewall.
- **Detect Malware Execution**: Identify when LaZagne is executed on the system.
- **Automate Threat Notifications**: Send alerts to the security team via Slack and email.
- **User Action Prompt**: Request user input on whether to isolate the compromised machine.
- **Automate Machine Isolation**: Automatically isolate the infected machine upon user approval.
- **Update on Action Taken**: Inform the security team about the isolation status and next steps.

## Skills Acquired
- Installing and configuring Windows Server 2022.
- Configuring and using EDR tools for malware detection.
- Setting up and managing SOAR platforms for automated incident response.
- Integrating security tools to create cohesive workflows.
- Automating notifications and user prompts through communication platforms.
- Implementing decision-based automation for incident remediation.

## Tools Used
- **Windows Server 2022**: Operating system for testing.
- **LaZagne**: Tool for simulating credential access attacks.
- **LimaCharlie**: EDR platform for detection and response.
- **Tines**: SOAR platform for orchestrating automated workflows.
- **Slack**: Platform for real-time notifications.
- **Email**: Medium for detailed alerts and user prompts.

## Implementation Steps
1. **Environment Setup**:
   - Install Windows Server 2022.
   - Disable firewall to facilitate malware installation.
   - Set up Slack and Tines for notifications and automation.
   - Deploy LimaCharlie agent and configure detection rules.

2. **Execution of Hack Tool**:
   - Simulate infection by executing LaZagne.

3. **Detection by LimaCharlie**:
   - Detect and log the presence of LaZagne as a threat.

4. **Processing by Tines**:
   - Initiate automated workflow and send alerts via Slack and email.

5. **User Prompt for Action**:
   - Email includes options for isolating the machine.

6. **User Response Handling**:
   - If "YES", isolate the machine and notify via Slack.
   - If "NO", prompt further investigation.

## Impactful Results
- **Rapid Detection**: Immediate identification of threats.
- **Automated Notifications**: Swift alerts to the security team.
- **User-Driven Response**: Empower users to make isolation decisions.
- **Efficient Isolation**: Quick isolation of threats upon approval.

## Conclusion
The integration of SOAR and EDR platforms enhances cybersecurity operations by automating incident response processes. This project demonstrates the power of combining LimaCharlie’s detection capabilities with Tines’ orchestration features to achieve rapid threat mitigation and improve security posture.
