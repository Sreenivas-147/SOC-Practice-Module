# 🛡️ Splunk Installation and Configuration on Ubuntu/Linux Machine  
#SOCPractice | #CybersecurityJourney**

Hello connections 👋,  
Today I worked on installing and configuring **Splunk** — a powerful SIEM (Security Information and Event Management) tool — on an **Ubuntu Linux machine** as part of my cybersecurity learning journey.

---

## 🎯 Objective  
The aim was to install and configure **Splunk Enterprise** locally to **collect, monitor, and analyze security logs** — an essential step in setting up a Security Operations Center (SOC).

---

## 🧪 Lab Setup  
- **System**: Ubuntu 22.04 LTS  
- **Tool**: Splunk Enterprise Free Version  
- **Access**: Terminal-based Installation  

---

## 🔧 Installation Steps  

### Step 1: Download Splunk  
```bash
wget -O splunk-9.3.0-51ccf43db5bd-linux-2.6-amd64.deb \
"https://download.splunk.com/products/splunk/releases/9.3.0/linux/splunk-9.3.0-51ccf43db5bd-linux-2.6-amd64.deb"

sudo dpkg -i splunk-9.3.0-*.deb
```

---

### Step 2: Enable as a Service  
```bash
cd /opt/splunk/bin
sudo ./splunk enable boot-start --accept-license
sudo ./splunk start
```
> 🔐 Set up your admin username and password when prompted.

---

### Step 3: Access Web Interface  
Open browser and go to:  
🔗 [http://localhost:8000](http://localhost:8000) or  
🔗 `http://<your-server-ip>:8000`

---

## ✅ Outcome  
- ✔️ Successfully installed Splunk  
- ✔️ Configured it to run as a system service  
- ✔️ Logged in via web to start monitoring logs  

---

## 🙌 Gratitude  
Big thanks to my mentors and the cybersecurity community for their constant support.

---

**#CyberSecurity #SOC #Splunk #Linux #SIEM #StudentLearning #Ubuntu #Infosec #LinkedInLearning #SplunkOnLinux**
