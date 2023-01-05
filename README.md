# In-depth Analysis of Colonial Pipeline Cyberattack

The President of the USA, Joe Biden declared a state of emergency in May 2021 as a result of the colonial pipeline ransomware attack that occurred on the 7th of May 2021 which was the largest cyberattack on an oil infrastructure in the history of the United States as at the time of occurrence.  
The colonial pipeline which controls nearly fifty percent of the gasoline, jet fuel and diesel had to shut down their 5,500-mile pipeline delivering fuel from Gulf coast refineries to major East coast markets due to a ransomware attack.  It did so out of concern that the malware that had infected its back-office functions could make it difficult to bill for fuel delivered along the pipeline or even spread into the pipeline’s operating system. The attackers exfiltrated 100 gigabytes of data within a two-hour window and thereafter infected the Colonial Pipeline IT network with ransomware. A ransom of 75bitcoin was paid to receive the keys to decrypt the data, however, the Department of Justice recovered 63.7bitcoin from the attackers.
Cybersecurity experts also noted that Colonial Pipeline would never have had to shut down its pipeline if it had more confidence in the separation between its business network and pipeline operations. 
This led to a spike in gasoline prices, panic buying and localized fuel shortages.

## Causes
The attack occurred using a legacy Virtual Private Network VPN that did not have Multi-Factor Authentication MFA in place that means with only a username and password the attacker gained access to the system
Lack of separation between data management and the actual operational technology

## Recommendations
1. Enforcing MFA to access the internal network will reduce the possibility of gaining access with credentials only
Authentication- verifying that you are the legitimate owner of an account. There are three methods of authentication 
- Something you know – By remembering a piece of information and inputting it you can prove that you are who you say are. Examples:  Passwords, Passphrases and PIN
- Something you have – By possessing something you can prove that you are a given entity Examples: Token, memory cards, passcode grid
- Something you are – Presenting a unique attribute tied to your physical make up. Examples: Palm vein scan, thumbprints, facial recognition, Voice recognition, retina and iris scan
Using only one of the methods of authentication is single-factor authentication and granting users access only after successfully demonstrating or displaying two or more of these methods is known as multi-factor authentication (MFA). 
2. Applying the principle of least privilege and need to know for all employees- Least privilege involves giving someone the least amount of access they need to do their job and nothing extra while need to know involves granting someone access to resources when they need it and revoke it when it is no longer required- The proper combination of these enables proper restriction of access. 
3. Deploying a zero-trust model in securing critical assets which means that all requests must be properly authenticated and authorized before being granted access. The zero-trust model is also based on the principle that internal and external threats will always be present, therefore every user, device and connection must prove that it is allowed to get access before it is given access.
This can also be configured to consider the location where the request is coming from, device compliancy -using a corporate device or not, type of application and type of user access. Access is only granted when the user meets or exceeds a set threshold. 
So, a user from an unknown location, using a non-corporate device and unable to authenticate with MFA will not be able to gain access into the internal network
4. Proper network segmentation using layers of defence. It is good security practice to ensure that any system with sensitive data must reside on the private(internal) network and must not be accessible from the public network - the internet.
 
5. Knowing your company assets including applications and setting up patching cycles to ensure patches are implemented in a timely manner to manage vulnerabilities.
 
6. Data loss protection devices can be configured to flag off when an amount of data is being sent out of the network for an IT security personnel to review and authorize large data transfer out of the network.
 
7. Lastly, knowing your systems and setting up a baseline to be able to know the normal and be able to quickly identify abnormalities 

## References
- https://en.wikipedia.org/wiki/Colonial_Pipeline_ransomware_attack
- https://www.bloomberg.com/news/articles/2021-06-04/hackers-breached-colonial-pipeline-using-compromised-password
- https://www.reuters.com/business/colonial-pipeline-ceo-tells-senate-cyber-defenses-were-compromised-ahead-hack-2021-06-08/
- https://www.nytimes.com/2021/05/14/us/politics/pipeline-hack.html
- https://www.techtarget.com/whatis/feature/Colonial-Pipeline-hack-explained-Everything-you-need-to-know?amp=1
- https://seemorerocks.is/usdot-declares-emergency-over-colonial-pipeline-shutdown/
