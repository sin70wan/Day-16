-----------------------
*Anonymity and DOS*
● Anony/unknown 
● When Black Hat Hackers do Security tests on some target, They will be unknown
           Methods of Anonymity
 ● There are several ways to be protected or to be Anonymous on the internet. 
 ● These methods can change our identity,location or personality. 1. Proxychains 2. Tor Network 3. VPN 4. Mac change 5. Incognito 6. Secured OS 7. Temp mail 8. Temp number
 Proxy Server (intermediary): a proxy server is a system or router that provides a gateway between users and the internet. Therefore, it helps prevent cyber attackers from entering a private network. 
 ProxyChains :We have a lot of proxy lists so our request will pass through lot of proxys.
 Types of ProxyChains Based on the path we follow There are 4 Types of proxychains. 
 1. Dynamic chain 
 2. Strict Chain 
 3. Round Robin Chain 
 4. Random Chain
   1.Dynamic Chain Dynamic Chaining is That way the proxy Servers are chained is as the proxy list given. ●If there is any server that is not working it will be skipped. 
 ● If any of them doesnt work it will be broken and display errors
 2.Strict Chain : All Proxies chained in the order as the are listed. All proxies Have to be up and working, if 1 is not working it will display error
 3.Round Robin chain: It follows the order of the proxy list  It will skip if 1 proxy is not working If all the proxies not working it will start again and check them. This makes it different from Dynamic chain
 4.Random Chain : It will choose some Proxy server Randomly and creates chain in random order.  Not working will be Skipped!  Each Request will be in random sequence of servers.
 #Accessing with proxychains 1. Add “proxychains4” in front of any command.
           T.O.R/The Onion Routing/ Network 
 ● Tor is an open-source privacy network that enables anonymous web browsing. 
 ● The worldwide Tor computer network uses secure, encrypted protocols to ensure that users' online privacy is protected. 
 ● Tor users' digital data and communications are shielded using a layered approach that resembles the nested layers of an onion.
          torghost 
 ● Clone it from github ○ https://github.com/SusmithKrish nan/torghost 
 ● Install tor 
 ● Open it!
 ● Your last Proxy IP will be shown(Public IP)
           VPNs(Virtual Private Network)
● A VPN establishes a secure, encrypted connection between your computer and the internet, providing a private tunnel for your data and communications while you use public networks
           Mac Changer
● SO , if we changed that we can change our device id. 
● We can use tool called “macchanger” on kali 'sudo macchanger -r wlan0'
● 1st turn off the interface you want to change. 
● Turn it on now! 
● You can add your specific MAC with -m option
            Incognito mode 
● This is a mode that browsers have. 
● This will help you to have a browser with out logging your history,cookies,cache,.. 
● This will help you when you are try to surf some site but if you dont need the site to know your identity, you can use this because it doesnt have any recording process.
     Temporary mail 
● While You do some pentest you dont have to expose your email and profile for this purpose u need fake emails, 
● but if you dont have to time create one you can use fake email providers. 
● https://temp-mail.org/ 
● It have a browser extention too
Deep web 
● The deep web refers to all the web pages and data that are not indexed by search engines and cannot be accessed through traditional search methods. It includes content that is protected by passwords, databases, and other security measures.
DARK WEB 
● The dark web is a part of the internet that isn't indexed by search engines
● Their link ends with .onion , this is because it uses TOR networks. 
● Also this kinds of links won’t be opened by normal browser. 
● For this purpose we need a special .onion reading browser, ○ Example: Tor browser
● There are Specific OS that are planned and Made for darkweb access. ● Like, ○ Tails OS ○ Whonix OS ○ Qube OS
Also TOR browser is so slow, based on your internet speed, it might not show you the correct result use command
sudo apt install torbrowser-launcher
      DOS and DDOS Attacks 
● DoS is short for Denial-of-Service attacks. 
● DDoS stands for Distributed Denial-of-Service attack. 
● It's used to crash a website by overwhelming the network with access requests from a computer. This method also crashes a targeted website and makes it unavailable to legitimate users.(like Mac spoofing)
● It is purposeful attack 
● On DDOS, the request will be sent from DIfferent Computers/hosts this will make the attack harder.
● Techniques: 
○ SYN floods ■ Sending lots of SYN 
○ Service Request floods ■ Create many connections 
○ Application level DOS ■ Exploiting vulns like : Buffer Overflow ,SQL injection
          Tools For DOS 
    1. SolarWinds Security Event Manager (SEM)
    2. ManageEngine Log360 
    3. HULK 
    4. Tor’s Hammer 
    5. Slowloris 
    6. LOIC 
    7. Xoic 
    8. DDOSIM 
    9. RUDY 
    10. PyLoris