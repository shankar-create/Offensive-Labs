# Offensive-Labs
Dictionary Attack lab description: 
This lab builds a three-node VirtualBox topology (Kali attacker,
Ubuntu target with OpenSSH and a simple PHP/SQLite web
app, and Windows Server target with RDP) to demonstrate
password attack techniques and mitigations. Using Hydra, the
attacker performs online dictionary attacks against SSH, RDP
and the web login form; using Impacket/secretsdump and
Hashcat, NTLM hashes are extracted and cracked offline. The
defensive phase implements Fail2Ban, local account lockout
policies, Network Level Authentication (NLA) and firewall
restrictions; the report compares attack success rates before
and after hardening and discusses why offline hash-cracking
remains a risk.
