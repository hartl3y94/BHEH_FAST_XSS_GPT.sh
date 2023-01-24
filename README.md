# BHEH_FAST_XSS_GPT.sh

<p align="center">
<a href="https://www.blackhatethicalhacking.com"><img src="https://pbs.twimg.com/profile_banners/770898848197795840/1650879597/1500x500" width="600px" alt="BHEH"></a>
</p>
<p align="center">
<a href="https://www.blackhatethicalhacking.com"><img src="https://www.blackhatethicalhacking.com/wp-content/uploads/2022/06/BHEH_logo.png" width="300px" alt="BHEH"></a>
</p>

<p align="center">
The tool is written by Black Hat Ethical Hacking with the help of #ChatGPT as an experimentation, with a lot of hours spent modifying the code generated by ChatGPT and is designed for Offensive Security and XSS (Cross-Site scripting) attacks. 
</p>

# Description

The tool uses the Wayback Machine to fetch URLs and filters them based on parameters contained in the URLs. It then uses a remote XSS payload list from Github to send GET requests with the payloads to the filtered URLs. 

It also includes a feature that generates a random Sun Tzu quote for offensive security and uses lolcat to display colorful outputs and ASCII art. It also includes a check to ensure that the user is connected to the internet before running it. 

What is special about this tool is that technically, by changing the payload wordlist, you could do more injection based attacks. This means you can modify it, so it can check for SQL Injections, OS Command Injection and so on! - If you do change it, send us a push notification so we can add it!

# Features:

• Automatically fetches URLs from the Wayback Machine

• Filters URLs based on parameters contained in the URLs

• Uses a remote XSS payload list from Github

• Sends GET requests with payload list to URLs

• Detects and reports possible XSS vulnerabilities

• Creates a folder with the domain name to save results

• Prints final message with number of possible vulnerable URLs

• Saves result URLs in a file

• Display a random Sun Tzu quote for offensive security

• Check if the user is connected to the internet before running the tool

• Provides a way to append payloads to the URLs

• Output the full URL with payload

This tool with also display a summary feature that displays the total number of possible XSS injections found, along with a list of affected URLs, the payload used, and the response code, at the end.

# Requirements:

• waybackurls: This tool can be installed by running go get github.com/tomnomnom/waybackurls

• cURL: This tool is commonly pre-installed on Kali Linux and Ubuntu, but can be installed by running apt-get install curl on Ubuntu or brew install curl on MacOS

• figlet: This tool can be installed by running apt-get install figlet on Kali Linux or Ubuntu or brew install figlet on MacOS

• lolcat: This tool can be installed by running gem install lolcat

• wget: This tool is commonly pre-installed on Kali Linux and Ubuntu, but can be installed by running apt-get install wget on Ubuntu or brew install wget on MacOS

# Installation

`git clone https://github.com/blackhatethicalhacking/BHEH_FAST_XSS_GPT.sh.git`

`cd BHEH_FAST_XSS_GPT.sh`

`chmod +x BHEH_FAST_XSS_GPT.sh`

`./BHEH_FAST_XSS_GPT.sh`

# Screenshots

**Main Menu**

![alt text](https://i.ibb.co/6JnTt3B/Main.png)

**Attack in Progress**

![alt text](https://i.ibb.co/0fGDnNZ/Attack.png)

# Compatibility: 

This tool has been tested on Kali Linux, Ubuntu and MacOS.

# Payload Wordlist:

To change the list of payloads, you can edit the tool and set another URL.

# Disclaimer

This tool is provided for educational and research purpose only. The author of this project are no way responsible for any misuse of this tool. 
We use it to test under NDA agreements with clients and their consents for pentesting purposes and we never encourage to misuse or take responsibility for any damage caused !

# Support

If you would like to support us, you can always buy us coffee(s)! :blush:

<a href="https://www.buymeacoffee.com/bheh" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>