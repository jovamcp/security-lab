\# 🔐 Web Security Lab



A vulnerable web application built for penetration testing practice and security education.



\## 🌐 Live Demo

https://security-labvul.netlify.app



\## ⚠️ Disclaimer

This application contains \*\*intentional vulnerabilities\*\* for educational purposes only.

Do not use in production environments.



\## 🎯 Vulnerabilities Included



| # | Vulnerability | Severity |

|---|---|---|

| 1 | Reflected XSS | High |

| 2 | Stored XSS | Critical |

| 3 | SQL Injection (simulated) | High |

| 4 | Missing Subresource Integrity | High |

| 5 | CSP unsafe-inline | Medium |



\## 🛠️ Tools Used

\- \*\*OWASP ZAP\*\* — Automated vulnerability scanning

\- \*\*Mozilla HTTP Observatory\*\* — Security headers analysis

\- \*\*Burp Suite\*\* — Manual penetration testing



\## 🚀 How to Run Locally



```bash

git clone https://github.com/jovamcp/security-lab.git

cd security-lab

python -m http.server 8080

```



\## 📋 Exercises



1\. Inject `<img src=x onerror=alert('XSS')>` in the search field

2\. Post a comment with HTML or script tags

3\. Login bypass with `' OR '1'='1`

4\. Inspect external scripts loaded without SRI

5\. Run OWASP ZAP automated scan against the live URL



\## 📊 Security Score

Mozilla HTTP Observatory: \*\*30/100 (D)\*\* — intentionally vulnerable



\## 🔧 CI/CD Pipeline

Automated deployment via GitHub Actions → Netlify on every push to `main`.

