# **How to Use**

<p>Choose your operating System</p>

<details>
 <summary><b> Windows</b></summary>
 
 ---
 
Open a [Elevated Command Prompt](https://www.tenforums.com/tutorials/2790-open-elevated-command-prompt-windows-10-a.html), type: 
```
netsh wlan show profile WiFi-name key=clear
```
and replace Wifi-name with your wifi name. If you do not know your wifi name, you can type: 
```
netsh wlan show profile
```

</details>

<details>
  <summary><b> Mac</b></summary>

---

Open [Terminal](https://support.apple.com/guide/terminal/open-or-quit-terminal-apd5265185d-f365-44cb-8b09-71a064a42125/mac) and type: 
```
security find-generic-password -ga Wifi-name | grep “password:”
```
and replace Wifi-name with your wifi name. You will get a pop-up window requesting your local adminitrator user, type it in and you should get the password

</details>
