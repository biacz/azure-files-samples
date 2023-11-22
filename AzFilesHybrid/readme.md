## Overview
The AzFilesHybrid PowerShell module provides cmdlets for deploying and configuring Azure Files, namely, cmdlets for domain joining storage accounts to your on-premises Active Directory, and configuring your DNS servers.

# Modifications
This has been modified to accept ADCredentials in case you want to run the AD parts of it with a different set of credentials. Most cmdlets are updated with their parameters and examples. I have only enabled AD creds for cmdlets that require specific permissions like write or set AD objects.
