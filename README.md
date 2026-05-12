#  Mini Vulnerability Scanner

A simple web-based Vulnerability Scanner built using HTML, CSS, and JavaScript.  
This project analyzes a given website URL and generates a basic security report based on simulated checks.

---

##  Features

- Scans website URL for basic vulnerabilities
-  Detects HTTPS (Secure / Not Secure)
-  Simulated Port Scan (Port 80 & 443)
-  Detects weak configurations (test/demo keywords)
-  Identifies outdated software (simulated)
-  Generates structured Vulnerability Report
-  Clean and modern UI

---

## Technologies Used

- HTML
- CSS
- JavaScript  

---

## 📂 Project Structure

```text
Vulnerability-Scanner/
│
├── index.html
└── README.md

```
---

## How It Works

1. User enters a website URL  
2. System performs checks:
   - HTTPS status  
   - Open ports (simulated)  
   - Weak configuration detection  
   - Outdated software detection  
3. Generates a vulnerability report  
4. Displays results in structured format  

---
## Site Examples
```text
https://github.com
https://www.w3schools.com/
https://old-demo-site.com/
http://legacy-system.com/
```
---

## How to Run

1. Download the project  
2. Open `index.html` in any browser  
3. Enter a URL  
4. Click **Scan**  
5. View the generated report  

---

## Example Output

```text
Vulnerability Report

❌ Not Secure (No HTTPS)
⚠ Port 80 (HTTP) - Open
⚠ Possible weak configuration detected
⚠ Outdated software detected
```

