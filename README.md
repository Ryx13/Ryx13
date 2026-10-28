# Eugene Ryan Dube

Offensive security — web applications and Active Directory.
Final-year BSc Computer Science, University of the Witwatersrand.

[ryxvoid.xyz](https://ryxvoid.xyz) · [linkedin](https://linkedin.com/in/ryxvoid) · [hack the box](https://profile.hackthebox.com/profile/019dff9b-353d-71f9-afc4-ccdd2c9bb57d) · [ryanmuzi13@gmail.com](mailto:ryanmuzi13@gmail.com)

---

## 01 · state

I learn systems by attacking them. Everything below is work I have done or am doing — no
aspirational skill lists.

Most of my time goes into web application security and Active Directory. I built
[rvr](https://github.com/Ryx13/rvr) because reconnaissance was the part I kept repeating
by hand: it decides what to run next from what it finds, correlates the results against
NVD CVEs, and writes the engagement report. Building the part that writes the report
taught me more about how findings actually land with a client than the scanning did.

---

## 02 · attack path

```text
  ┌───────────────┐
  │ enumeration   │──  nmap · ffuf · gobuster · enum4linux-ng
  └───────┬───────┘
          │
  ┌───────▼───────┐
  │ exploitation  │──  burp suite · nuclei · metasploit
  └───────┬───────┘
          │
  ┌───────▼───────┐
  │ credentials   │──  impacket · netexec
  └───────┬───────┘
          │
  ┌───────▼───────┐
  │ AD            │──  bloodhound · kerberoasting · ACL abuse
  └───────┬───────┘
          │
  ┌───────▼───────┐
  │ domain admin  │──  the point of the exercise
  └───────────────┘
```

Steps one to four I have practised, on retired machines and in my own lab. The last one
is what the CPTS path is for.

---

## 03 · capability, honestly

Every student profile claims everything. Here is where I actually am:

| area | where I actually am |
| --- | --- |
| **Enumeration** | Practised. It is what rvr automates, and what I do first on every machine. |
| **Web application** | Comfortable in lab conditions. Auth bypass, DOM and reflected XSS, CSRF, SQLi, RCE, TLS misconfiguration — exploited on purpose, then mitigated. |
| **Active Directory** | Learning. Enumeration is solid; attack paths, ACL abuse and lateral movement are in progress in my home lab. |
| **Reporting** | Practised on real work. Plain-language risk reports to non-technical leadership at TKN, and rvr's PDF output. |
| **Cloud** | ICCA certified, least hands-on. The gap I am closing next. |
| **Production engagements** | None yet. Labs, internships and coursework. |

---

## 04 · toolbelt

```text
enumeration    nmap · ffuf · gobuster · enum4linux-ng
web            burp suite · owasp zap · nuclei
exploitation   metasploit · impacket
active dir     bloodhound · netexec · kerberoasting
traffic        wireshark
reporting      rvr → nvd api → cvss → pdf
build          python · bash · c/c++ · typescript · java · sql
```

---

## 05 · changelog

```text
2027.04   BSc conferred — coursework complete 2026.12
2026.10   CPTS path, active
2026.06   MWR CyberSec — 16-week virtual internship, capstone compromised an
          enterprise-style web environment
2026.01   eJPT · ICCA
2025.08   ISC2 CC
2025.02   TKN Accounting — vulnerability assessments on internal financial
          infrastructure, CVSS-rated findings, remediation guidance
2024.04   The Cimplicity Institute — offensive security mentorship programme
2024.02   BSc Computer Science, University of the Witwatersrand — began
```

---

Writing up HTB and TryHackMe methodology at [ryxvoid.xyz](https://ryxvoid.xyz). Open to
junior penetration testing and graduate security roles from January 2027; SOC roles
considered. Johannesburg — hybrid or remote.
