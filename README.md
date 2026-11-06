# Phishing Simulation & Risk Assessment Lab (GoPhish)

This is a hands-on project I worked on as part of my GRC training. I used GoPhish to carry out a controlled phishing simulation to understand how users can respond to phishing emails.

Beyond setting up the tools and running the simulation, I also looked at the results from a GRC lens — identifying control gaps and making recommendations based on the findings.

## What I worked on

- Set up GoPhish on a Kali Linux VM using VirtualBox.
- Configured Mailtrap as a sandbox SMTP service to test email delivery without sending emails to real inboxes.
- Created a phishing email using a VPN password expiry theme and built a cloned login page.
- Monitored and analysed the email open rate, link click-through rate and credential submission rate.
- Interpreted the results to identify potential risks and control gaps.
- Prepared a report covering the risk assessment, key findings, and recommendations.

## Why this project matters

Phishing is one of the ways attackers gain access to systems and sensitive information. Working on this project helped me understand that GRC goes beyond identifying risks — it also involves understanding how those risks affect an organisation, identifying where existing controls may be falling short, and recommending ways to reduce exposure.

For this simulation, I considered recommendations such as implementing MFA, improving security awareness training, and conducting regular phishing exercises.

## Key findings

| Metric | Result |
|---|---|
| Email Open Rate | 100% |
| Link Click-Through Rate | 100% |
| Credential Submission | Not captured due to a technical limitation with the cloned landing page. This is explained in the full project report. |

## Scope of the project

I carried out the entire simulation on my own machine in an isolated lab environment. No real users, organisations, or production systems were involved. All testing was done for learning and practical experience.
