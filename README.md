# Playground
Misc Projects, notes, and more

## vul 1
Missing security Headers 
## Vul 2
Exposed username and bio in URL
## vul 3
privilege escalation via IDOR
IDOR (Insecure Direct Object Reference)data_source can be manipulated by the user
Accepts arbitraru username=
## vul 4
Directory Structure
data/
## vul 5
XSS
change username, 
## Vul 5
LFI - local file inclusion vul
.without sanitizing or validating the input — making it vulnerable to LFI attacks.
Resolves real file paths, including:

/etc/passwd

/var/log/nginx/access.log

config.py

data/data_source.txt

