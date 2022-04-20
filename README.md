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
![image](https://user-images.githubusercontent.com/88451628/164322578-1e40a900-1b3b-40cd-a3be-540b669ed20c.png)

 
                                                    
Step2: Select the target victim and copy the BSSID
![image](https://user-images.githubusercontent.com/88451628/164322608-dbd1aff1-dfce-4fb5-b16c-581da99c5813.png)

 
                                                         
Step3: Start airodump-ng to collect authentication handshake
![image](https://user-images.githubusercontent.com/88451628/164322639-7fd71c66-5f4a-4755-97ea-3c7abe11468d.png)

 
                                                                               
Step4: Use aireplay-ng to deauthenticate the wireless client
![image](https://user-images.githubusercontent.com/88451628/164322658-30656fcd-dd84-499c-8074-f736f80e0d92.png)
 
                                                                    

2.2Malware Attack
Step1:Create a payload
![image](https://user-images.githubusercontent.com/88451628/164322699-74130d9b-fda6-4200-8afb-88db14177d99.png)

 
                                                               
Step2: After installing the payload to target device ,setting up exploit 
![image](https://user-images.githubusercontent.com/88451628/164322724-0ede2e2a-02d7-42b6-b2b2-eb720d2e5f98.png)

 
                                                            
2.3DoS attack
Flooding a private server (192.168.29.240) with HTTP requests . The server becomes slow then later crashes .
![image](https://user-images.githubusercontent.com/88451628/164322746-774edffa-ca60-45f6-8766-987d643b8cc9.png)

 
                                                                
3.RESULT:
3.1Dictionary attack: Run aircrack-ng to crack the pre-shared key.

![image](https://user-images.githubusercontent.com/88451628/164322456-aecd9c73-ba7c-4bd3-8145-ffdb84d8fc90.png)


  
                                      
3.2Malware Attack
Exploiting the victim device 

Listing installed apps in target device
![image](https://user-images.githubusercontent.com/88451628/164322778-f1a39706-1d83-4fc9-8643-5f21b8c73877.png)
 
				
Taking a web-snap from target device
![image](https://user-images.githubusercontent.com/88451628/164322845-3ad43da9-4a15-41df-9fdf-42681c03c2e5.png)

 
				



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


