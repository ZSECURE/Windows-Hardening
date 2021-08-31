# Windows-Hardening

Credit to Itai Grady - This is just a place to keep the tools alive becasue it's been taken off the TechNet Gallery website

## Net Cease - Hardening Net Session Enumeration
“Net Cease” tool is a short PowerShell (PS) script which alters Net Session Enumeration (NetSessionEnum) default permissions. This hardening process prevents attackers from easily getting some valuable recon information to move laterally within their victim's network.

Overview
Reconnaissance (recon for short) is a key stage within the Advanced Attackers kill chain. Once attackers have breached a single end-point, they need to discover their next targets within the victim's corporate network, most notably privileged users.

Once attackers had “zoomed in” on target users, they need to find out the computers they had logon to, in order to propagate to them and compromise their credentials. Applying the SMB Session enumeration via the NetSessionEnum method against the DC (or other file servers), allows the attackers to get that information. Recently, some frameworks (e.g. BloodHound) have automated that mapping process.

Original - https://gallery.technet.microsoft.com/Net-Cease-Blocking-Net-1e8dcb5b/file/165596/1/NetCease.zip  <br/>
WaybackURL - https://web.archive.org/web/20200318132221/https://gallery.technet.microsoft.com/Net-Cease-Blocking-Net-1e8dcb5b/file/165596/1/NetCease.zip

## SAMRi10 - Hardening SAM Remote Access in Windows 10/Server 2016
"SAMRi10" tool is a short PowerShell (PS) script which alters remote SAM access default permissions on Windows 10 & Windows Server 2016. This hardening process prevents attackers from easily getting some valuable recon information to move laterally within their victim's network.

Overview
Reconnaissance (recon for short) is a key stage within the Advanced Attackers' kill chain. Once attackers have breached a single end-point, they need to discover their next targets within the victim’s corporate network, most notably privileged users. In order to enable admins to harden their network against such recon attacks targeting local users, we had developed the “SAMRi10” (pronounced Samaritan) tool.

Original - https://gallery.technet.microsoft.com/SAMRi10-Hardening-Remote-48d94b5b/file/165593/1/SAMRi10.zip   <br/>
WaybackURL - https://web.archive.org/web/20200318211431/https://gallery.technet.microsoft.com/SAMRi10-Hardening-Remote-48d94b5b/file/165593/1/SAMRi10.zip
