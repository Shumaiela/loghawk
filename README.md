# DESCRIPTION
LogHawk is a Python-based log monitoring tool developed as part of the Lighthouse Labs Bootcamp Project. It  monitors various system logs (application, system, authorization, and access logs) for suspicious activities and potential security threats. When suspicious logs are detected, they are recorded in a comprehensive log file (comp_log.txt) for further analysis.

⚠️However, this script is not intended to be used for Real-World Security Monitoring of Log Files. It is simply an idea of how we can Monitor Log Files. 



# FEATURES
✅Real-time monitoring of multiple log types
✅Customizable detection rules for suspicious activities
✅Automated alert generation
✅CRON job integration for periodic execution
✅Comprehensive log recording for security analysis



# INSTALLATION 💻

**Ensure Python 3.x is installed**
python3 --version
******************************************************
**Install Python 3.X**
sudo apt-get install python3
******************************************************



# USAGE

**Running the script directly**
python3 log_hawk_proj.py
******************************************************
**Setting up CRON job for automated execution every 10 minutes:**
*/10 * * * * /usr/bin/python3 (path to the script file)/log_hawk_proj.py
******************************************************



# CUSTOMIZATION
Inside the def main() function add the path to your Access log file, Application Lof file, Auth log file and System Log file.

def main():

**Add Access Log file path here** 
    access_path = "/media/sf_shared/access.log"
******************************************************
**Add Application Log file path here**
    app_path = "/media/sf_shared/app.log"
******************************************************
**Add Auth Log file path here**
    auth_path = "/media/sf_shared/auth.log"
******************************************************
**Add System Log file path here**    
    system_path = "/media/sf_shared/system.log"
******************************************************



# DEPENDENCIES

✅Python 3.x
✅Standard Python libraries (re, os, datetime)



# LICENSE 📝
🛑Use the Script at your own Risk!🛑 

