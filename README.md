                         
<br/>
<div align="center">
<a href="https://github.com/ShaanCoding/ReadME-Generator">
<img src="https://ibb.co/SNSnCWC" alt="Logo" width="80" height="80">
</a>
<h3 align="center">Coupa Receiving Automater</h3>
<p align="center">
Services take forever some days, use this tool to automate your Coupa links.

<br/>
<br/>
  
<a href="https://github.com/VoydeYT/CoupaSR/issues">Report Bug .</a>

</p>
</div>

 ## About The Project

![Product Screenshot](https://ibb.co/Ydt0PyR)

Services that we must check as Non-Inventory T3's can be very tedious and just plain old annoying sometimes. So this python script, runs all the provided links from Coupa, references and compares the "Approved Invoiced" and "Received" values. When the values are all returned as the same, it will send a HTTPS POST to the slack link listed, and you've checked services for the day!
 ## Getting Started

Here's what you'll need:
 ### Prerequisites

Please install Python 3.12 to get started: 
https://www.python.org/downloads/release/python-3120/

Then please run the following commands in cmd:

- Installing os
  ```sh
  npm install os@latest -g
  ```
- Installing requests
  ```sh
  npm install requests@latest -g
  ```
- Installing WebDriver
  ```sh
  npm install WebDriver@latest -g
  ```
- Installing concurrent.futures
  ```sh
  npm install concurrent.futures@latest -g
  ```
 ### Installation

_This application is very simple! Follow the steps below._

1) Download and extract the contents onto your Desktop.
2) Run SRV1.1.py from inside of the extracted folder.
3) Let it run and open chrome on it's own, and it will let you know if anything goes wrong.

And that's it! The output will go to the slack webhook you provided inside of slackwebhook.txt. (This script is in beta, so there will be bugs, please report them)
 ## Usage

The usage of this python script is do for the user to provide mass amounts of Coupa links, and the script will scrape these links for the "Received" and "Approved Invoiced" values. When the same, it will have no output to user but will store the value. When they are different it will make a log file, which you can then go into and find out which Coupa PO does not have the same values.
 ## License

Distributed under the MIT License. See [MIT License](https://opensource.org/licenses/MIT) for more information.
 ## Contact

Jace Smith - Slack: @smijaceo - smijaceo@amazon.com

Project Link: [https://github.com/smijaceo/CoupaSR](https://github.com/VoydeYT/CoupaSR)
