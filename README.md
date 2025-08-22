# Log_parser
## 📌 Objectives

- Develop a Python script capable of parsing log files (e.g., system logs, Apache logs, or syslogs) to see if specific IP address appear.
- Identify key events such as potential threats(SQL injections, buffer overflow), errors, warnings, failed logins, or suspicious activity.
- Practice working with Linux environments by setting up and testing the parser inside an Ubuntu virtual machine.
- Gain hands-on experience in automation for log analysis and foundational cybersecurity monitoring skills.
<br><br>

## 🛠️Tools Used 

- Python 3 → for writing the log parser.

- Ubuntu Virtual Machine → to simulate a real server environment.

- Log Files (e.g., /var/log/syslog, Apache access logs).

- Regex (Regular Expressions) → for filtering specific patterns from logs.

- Nano → for script editing.

<br><br>

## Skills Learned

- Parsing and analyzing log data with Python.

- Using regular expressions to extract specific log events.

- Working in a Linux server environment (Ubuntu VM).

- Basic cybersecurity concepts like detecting failed logins or suspicious activity.

- Strengthening debugging and problem-solving skills when testing scripts.

<br><br>

## Steps Taken

<br><br>
### 1. Setup Environment

<img width="1419" height="671" alt="Screenshot (1142)" src="https://github.com/user-attachments/assets/9da5913e-12ad-4042-a4bb-404b9f7c9539" />

*Installed Ubuntu on a virtual machine(VirtualBox)*
<br><br>
- Ensured Python 3 and Apache were configured.
<br><br>
<br><br>

### 2. Log Collection

- Accessed web server logs (Apache/Nginx, if available) & Copied test logs for safe analysis.

<img width="1123" height="720" alt="Screenshot (1147)1" src="https://github.com/user-attachments/assets/31a7b054-1eb6-4dba-a4cc-1bb2f6df051e" />

*Access Apache access.log file and copied it to my_logs.log file*
<br><br>
<br><br>

### 3. Script Development

- Wrote a Python script that:
-  1. Opens the log file
   2. Gets user input
   3. Search & output the ip address in the log file  

<img width="1403" height="874" alt="Screenshot (1144)" src="https://github.com/user-attachments/assets/a446cfef-f0df-4cc5-8324-ffdc9ae62298" />

*Nano python script*
<br><br>
<br><br>
<img width="1396" height="877" alt="Screenshot (1145)" src="https://github.com/user-attachments/assets/a84cf288-442b-403f-909d-189f16cd2285" />

*Command line*
<br><br>
<br><br>

### 4. Testing & Debugging

- Configured the log parser to be python executable
- Ran the script against real Ubuntu access logs & Fixed parsing errors and refined regex patterns.
<img width="1389" height="878" alt="Screenshot (1146)" src="https://github.com/user-attachments/assets/394bca37-a65d-4005-8b1a-d847114bd97b" />
<img width="1397" height="866" alt="Screenshot (1147)" src="https://github.com/user-attachments/assets/0baf9b34-768b-4c94-b35d-b89ae5bc358e" />

*Command line 2&3*
<br><br>
<br><br>

### 5. Detecting Security Threats 
- Extended the script to detect potential attacks

  <img width="1389" height="865" alt="Screenshot (1149)" src="https://github.com/user-attachments/assets/5f3dd8d6-1875-4f26-a6f3-d9f2a4471579" />

*Nano python script 2*
<br><br>
<br><br>

## ✅ Conclusion

This project gave me practical exposure to log analysis, Python scripting, and Linux systems. By creating a log parser in a simulated Ubuntu environment, I built a foundation for cybersecurity monitoring and automation scripting. It also strengthened my ability to document, version control, and present technical work effectively for real-world applications.
