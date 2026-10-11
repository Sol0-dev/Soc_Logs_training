## NovaForge Supply Chain CTIA Exercise
> pahirapan logs

<img width="777" height="133" alt="image" src="https://github.com/user-attachments/assets/692b1d29-5ca8-4e5a-8ecc-8994ea6de504" />

You should see the three .log files (and nothing else).

## Step 1 - Get to know the Git server access log

In your own words, what does a kind=hook line describe?
It intercept the traffic to logs the data about the traffic 

Which field tells you who made the request?
user=
<img width="782" height="315" alt="image" src="https://github.com/user-atLook for critical or high-severity vulnerabilities, unexpected package installations, or packages flagged for malware/supply chain tampering.

How to verify: Run npm audit or inspect the log for lines containing high or critical severity advisories.tachments/assets/7b4e883d-9cd9-4bf5-a629-28987b927344" />

## Step 2 - How big is this dataset?

Record the line counts. Does anything surprise you?
Yes, the jenkins 

### How to spot suspicious activity

Look for repeated failed authentication attempts, unexpected IP addresses accessing repositories, or unauthorized webhook triggers pointing to external URLs.
How to verify: Run grep -i "fail" gitea_git_and_webhook.log or check for status codes like 401 Unauthorized and 403 Forbidden.

2.Check Jenkins logs for build tampering or injected scripts:
jenkins_ci_builds.log

Look for unauthorized job triggers, unexpected environment variable changes, 
aborted builds, or unknown shell scripts executing during the build phase.How to verify: Search for keywords like FAILURE, ABORTED, or unauthorized user 
accounts initiating builds via grep -E "FAILURE|Aborted by" jenkins_ci_builds.log.

<img width="1916" height="598" alt="image" src="https://github.com/user-attachments/assets/0d463bd4-647a-4c66-9c2d-cb8578b60476" />

<img width="745" height="114" alt="image" src="https://github.com/user-attachments/assets/6ae09991-4801-4a11-b735-5b81d6a7b50a" />



