[Cisco Talos Advisory](https://blog.talosintelligence.com/2021/03/threat-advisory-hafnium-and-microsoft.html)

Cisco Talos have released a number of Snort rules which can detect / block the behavior as follows –

- CVE-2021-26857 — 57233-57234
- CVE-2021-26855 — 57241-57244
- CVE-2021-26858 & CVE-2021-27065 — 57245-57246
- CVE-2021-24085 — 57251
- CVE-2021-27065 — 57252-57253
- Html.Webshell.Hafnium — 57235-57240

There is also a ClamAV signature – Win.ASP.MSExchangeExploit

>  NOTE: “*All organisations using the affected software should prevent external access to port 443 on Exchange Servers, or set up a VPN to provide external access to port 443. This will ensure that only authenticated and authorized users can connect to this service. However, this action will only protect against the initial step of the attack.*“

