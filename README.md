# Detection-Response
INTRODUCTION:
Objective:
Ethical hacking can prevent cyber-terrorism and terrorist attacks, ensuring the safety of the nation. Hackers can identify potential entry points from an attackers' perspective, allowing you the chance to fix them before an attack.Despite the rapidly evolving nature of cybercriminal activities, ethical hackers have a number of tools available at their disposal to create a solid line of defense.
1.DoS attack
DOS is an attack used to deny legitimate users access to a resource such as accessing a website, network, emails, etc. or making it extremely slow. ... This type of attack is usually implemented by hitting the target resource such as a web server with too many requests at the same time.
 The goal of this attacks is to exhaust the target’s resources to create a denial-of-service.
2.Dictionary attack
A dictionary attack is a method that consists of breaking into a password-protected computer or server (in this case a Wi-Fi network) by systematically entering every word in a dictionary as a password. Dictionary attack is a form of brute force attack technique for defeating a cipher or authentication mechanism by trying to determine its decryption key or passphrase by trying thousands or millions of likely possibilities, such as words in a dictionary.
Dictionary attacks often succeed because many people have a tendency to choose short passwords that are ordinary words or common passwords; or variants obtained, for example, by appending a digit or punctuation character.
3.Malware Attack
The purpose of malware is to intrude on a machine for a variety of reasons.Malware or malicious software is certainly dangerous, and in some cases, it can be incredibly dangerous, and threaten to compromise your online banking, or lock away all your data so you can't reach it forever. It always pays to think before you click on any link or download any file, and to use a good antivirus app.
Ethical Hacking is an authorized practice of bypassing system security to identify potential data breaches and threats in a network. The company that owns the system or network allows Cyber Security engineers to perform such activities in order to test the system’s defenses. Thus, unlike malicious hacking, this process is planned, approved, and more importantly, legal
Ethical hackers aim to investigate the system or network for weak points that malicious hackers can exploit or destroy. They collect and analyze the information to figure out ways to strengthen the security of the system/network/applications. 

IMPLEMENTATION:

2.1.Dictionary attack

Step1:  Start the wireless interface in monitor mode
 
                                                    
Step2: Select the target victim and copy the BSSID
 
                                                         
Step3: Start airodump-ng to collect authentication handshake
 
                                                                               
Step4: Use aireplay-ng to deauthenticate the wireless client
 
                                                                    

2.2Malware Attack
Step1:Create a payload 
 
                                                               
Step2: After installing the payload to target device ,setting up exploit 
 
                                                            
2.3DoS attack
Flooding a private server (192.168.29.240) with HTTP requests . The server becomes slow then later crashes . 
 
                                                                
3.RESULT:
3.1Dictionary attack: Run aircrack-ng to crack the pre-shared key.

![image](https://user-images.githubusercontent.com/88451628/164322456-aecd9c73-ba7c-4bd3-8145-ffdb84d8fc90.png)


  
                                      
3.2Malware Attack
Exploiting the victim device 
Listing installed apps in target device
 
				Fig 3.2.1
Taking a web-snap from target device
 
				Fig 3.2.2



4.CONCLUSION:
 The primary threat to any organization's security is a hacker: learning, understanding, and implementing how hackers operate can help network defenders prioritize potential risks and learn how to remediate them best
Ethical hackers are hired by organizations to look into the vulnerabilities of their systems and networks and develop solutions to prevent data breaches. Consider it a high-tech permutation of the old saying “It takes a thief to catch a thief.”
Ethical hackers are hired by organizations to look into the vulnerabilities of their systems and networks and develop solutions to prevent data breaches. Consider it a high-tech permutation of the old saying “It takes a thief to catch a thief.”
They check for key vulnerabilities include but are not limited to:
•	Injection attacks
•	Changes in security settings
•	Exposure of sensitive data
•	Breach in authentication protocols
•	Components used in the system or network that may be used as access 

 
				Fig 4.1


