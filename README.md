# Nikto Vulnerability Scan Report

## 🔍 Target:
`http://testphp.vulnweb.com`

## 🛠 Tools Used:
- Nikto (Web vulnerability scanner)

## 🧪 Scan Summary:
- Web server detected: Apache/2.2.X
- Found several outdated software versions
- Directory listing enabled on `/images/`
- Admin login page found at `/admin/`
- Potential XSS in `/search.php`

## 📌 Key Issues Found:
- X-Frame-Options header missing (Clickjacking risk)
- Directory indexing enabled
- Unsecured admin panel
- phpinfo page exposed

## ✅ Recommendation:
- Disable directory listing
- Restrict access to admin and sensitive directories
- Update web server and remove unnecessary files
- Implement HTTP security headers

## 📁 Output File:
`nikto_scan_results.txt` contains full scan results.

---

