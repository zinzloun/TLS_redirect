# TLS_redirect
## Simple resilient TLS reverse shell architecture

Here I will illustrate how to implement a simple but effective Redteam architecture to serve a reverse shell. Following the diagram:
<br>![Screenshot](RedTLS.png)<br>
I set up my ParrotOS VM to act as TLS redirect to a CentOS server that acts as attacker. Since in a real engagment it is probable that the front end will be <i>burnt<i> using this simple approach.

