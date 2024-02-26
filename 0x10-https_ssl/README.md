0x10. HTTPS SSL
Resources:books:
Read or watch:

What is HTTPS?
What are the 2 main elements that SSL is providing
HAProxy SSL termination on Ubuntu16.04
SSL termination
Bash function
Learning Objectives:bulb:
What you should learn from this project:

What is HTTPS SSL 2 main roles
What is the purpose encrypting traffic
What SSL termination means
0. HTTPS ABC
As for project 0x07, use numbers in your answer file.
1. World wide web
Configure your domain zone so that the subdomain www points to your load-balancer IP (lb-01). Let’s also add other subdomains to make our life easier, and write a Bash script that will display information about subdomains.
2. HAproxy SSL termination
“Terminating SSL on HAproxy” means that HAproxy is configured to handle encrypted traffic, unencrypt it and pass it on to its destination.
3. No loophole in your website traffic
A good habit is to enforce HTTPS traffic so that no unencrypted traffic is possible. Configure HAproxy to automatically redirect HTTP traffic to HTTPS.
