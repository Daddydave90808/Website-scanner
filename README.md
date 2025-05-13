# Website-scanner
Website Vulnerability Scanner Script


A Python script that scans a target website for common vulnerabilities like SQL Injection, Cross-Site Scripting (XSS), and Directory Traversal. Designed to support web application security assessments, aligning with penetration testing skills.
Installation:
Install Python 3.x.
Install required library: pip install requests.
Usage:
Run the script: python website_vuln_scanner.py -url <target_url> -o <output_file>
Example: python website_vuln_scanner.py -url http://testsite.com -o scan_results.txt
Note: Use on authorized systems only, as unauthorized scanning may be illegal.
Output:
Results saved to a text file (e.g., vuln_scan_results.txt) and a JSON file (vuln_scan_results.json).
Console output shows vulnerability status and details.
