<p align="center"><img src="https://massgrave.dev/img/logo_small.png" alt="MAS Logo"></p>

<h1 align="center">Microsoft  Activation  Scripts (MAS)</h1>

<p align="center">Open-source Windows and Office activator featuring HWID, Ohook, TSforge, and Online KMS activation methods, along with advanced troubleshooting.</p>

<hr>
  
## How to Activate Windows / Office / Extended Security Updates (ESU)?

### Method 1 - PowerShell ❤️

1. Click the **Start Menu**, type `PowerShell`, and open it.

2. Copy and paste the code below and press **Enter.**  
   - For **Windows 8.1, 10 and 11**:
     ```
     irm https://get.activated.win | iex
     ```
	 If the above is blocked (by ISP/DNS), try this (needs updated Windows 10 or 11):  
	 ```
	 iex (curl.exe -s --doh-url https://1.1.1.1/dns-query https://get.activated.win | Out-String)
	 ```
	- **Script not launching? Use the below-listed Method 2.**

3. In the menu that appears, type the number corresponding to one of the **Green** options.

---

### Method 2 - Traditional (Windows Vista and later)

1.   Download the script:
      *   [**MAS_AIO.cmd**](https://dev.azure.com/massgrave/Microsoft-Activation-Scripts/_apis/git/repositories/Microsoft-Activation-Scripts/items?path=/MAS/All-In-One-Version-KL/MAS_AIO.cmd&download=true) 
