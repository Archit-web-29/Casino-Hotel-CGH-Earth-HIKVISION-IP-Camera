# Casino-Hotel-CGH-Earth-HIKVISION-IP-Camera

## *I would not be held reponsible for any wrongdoing using my GitHub Repository*
## *Any hacking or wrongdoing done by an individual will be done on their own risk and responsibility*
## *Always hack using permission and ethically*
## *Everything below is for educational purposes only*

This repository will give you access to the HIKVISION IP Camera of the Casino Hotel CGH Hotel.

The username of the WiFi was already leaked from the frontend of the network. The password was brute forced using a simple python code.
Username - admin
Password - admin

The name of the WiFi is CGH Hotel and it is a captive WiFi. The password was your room number and your last name. After connecting to the Free WiFi, I used NMAP (Network Mapping) to find all the available and open ports. I saw PORT 53/tcp, status OPEN, and running service domain - 53/tcp  open  domain. This was list over 30 times, strongly stating that the port belonged to an IP Camera. Then using the leaked username and password, I was able to accesss the live video footage of the camera. 

Using the website 'DNS Leak Test' and some simple requests library python code, I was able to find the PUBLIC IP address of the CGH Hotel WiFi - 117.193.165.172

After finding the PUBLIC IP Address, I was able to make a link that would allow anyone from anywhere in this world to access live camera footage of Casino Hotel CGH Earth, Kochi, Kerala, India. On clicking the below links, you would have gained access to the live camera footage:
http://117.193.165.172
rtsp://admin:admin@117.193.165.172:554/Streaming/Channels/101

All this would not have been possible without:
1. DeepSeek AI - Hangzhou DeepSeek Artificial Intelligence Basic Technology Research Co., Ltd
2. ChatGPT - OpenAI Group PBC
3. NMAP - Network Mapper by Gordon Lyon
