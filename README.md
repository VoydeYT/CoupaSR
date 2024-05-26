# CoupaSR
This tool automates checking the links in "CoupaLinks.txt" references the Received and Approved Invoice values and verifies that they are all the same value. This program is in beta, there will be bugs.

**To use, you will need the following installed:**
-Python 3.12 (https://www.python.org/downloads/release/python-3122/)
-Chromium (https://developer.chrome.com/docs/chromedriver)

**For repositories you will need: **
os
requests
selenium import webdriver
datetime import datetime
concurrent.futures

**Instructions:**

It's pretty simple!
1) Make sure all requirements are installed and are up to date
2) Run SRV1.1
3) Let it open all the links provided into coupalinks.txt
4) It will reference all values, and if successful with no errors, it will ouput to the slack webhook i've put in.

I understand that the slack webhook will need to be altered for others users in the future, but this is a beta build.
