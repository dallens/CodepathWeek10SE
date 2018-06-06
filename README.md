# CodepathWeek10SE
Repo for CP Week 10 Social Engineering 
# Project 10 - Social Engineering

Time spent: 15 hours spent in total

> Objective: Learn and demonstrate use of Social Engineering tools

## Lab

### Milestone 1
The following shows the successful creation of a single email attack creation using the Social Engineering Toolkit on Kali. The png with the Google email account is the email created using SET and sent via Kali. The png of Kali is proof of creation of the email. 
![](https://github.com/dallens/CodepathWeek10SE/blob/master/w10_LabM1Gmail.png)

![](https://github.com/dallens/CodepathWeek10SE/blob/master/w10_LabM1Kali.png)

### Milestone 2
The following pngs show the successful creation of the spear phishing email with windows exploit payload. As mentioned in the lab write-up, Google did not allow the sending if the email. Instead, the error mentioned in the instructions displayed, indicating that Google blocked the exploit payload.
![](https://github.com/dallens/CodepathWeek10SE/blob/master/w10_LabM2Kali.png)

![](https://github.com/dallens/CodepathWeek10SE/blob/master/w10_LabM2Kali2.png)

### Milestone 3
These pngs show the successful creation of the fake Facebook site, using the SET. The credentials entered were captured by Kali, as described in the lab instructions.
![](https://github.com/dallens/CodepathWeek10SE/blob/master/w10_fakefb.png)

![](https://github.com/dallens/CodepathWeek10SE/blob/master/w10_M3capture.gif)

### Milestone 6

1. What vulnerabilities were beyond the control of the user?
In the video, the vulnerabilities outside of Keven Roose's control included the vulnerability of the cell phone company's support personnel to social engineering. They potentially overlooked policy and company best practices because they felt sorry for Jessica Clark's engineered fake scenario with the sounds of a crying baby and the desperate pleas for help into an account. In the Mat Honan story, the security policies of Amazon did not constitute robust authentication factors, neither did Apple's policy. Aside from not using these companies, Honan could not control the poor authentication of these companies. Likewise, if the Apple support personnel did not follow procedures, as Apple claims, Honan had no way of controlling for the personnel's vulnerability to social engineering or failure to comply with policy. Further, back in the Roose film, there was mention of the vulnerability of infrastructure and that many would be collateral damage for relying on the energy/satellite/industrial systems. The system's vulnerabilities are not under the user's control.

2. What if anything could have been done by the user to mitigate the severity of the attack?
For Roose, extremely vigilant security hygiene around email links and proper OS alert behavior would have helped prevent, but to mitigate severity of complete compromise requires separate random passwords with differing username credentials and little account linking, systems that are patched religiously, and monitoring of suspicious account resets or activity. Anything to create defense in depth to slow the attack and potentially discover it before complete compromise.

For Honan, the linkage of multiple accounts and similar information as authentication for each was what led to high severity. Likewise, the features which allowed remote wipe with no mitigating backup services for the MacBook or iPhone produced incredible data loss and downtime. Backup and recovery (with a non-linked account and two-factor authentication) with an acceptable RPO and RTO would have helped tremendously. The challenge is that the most common two-factor methods (email and cell) were in a disaster state and would have potentially caused a DoS on the backup and recovery if the authentication to those services relied on the email account and cell phone.

*Now, think back to the fake Facebook login scenario above. Assuming a successful compromise, in which the user's Facebook username and password were successfully intercepted, answer the following:*

3. What could the user do to mitigate this, making a successful login impossible for the attacker even with the credentials? (Hint: FB offers this as an option; not all sites do)
Two-factor authentication would require that the user have access to either another account (for a PIN) or a cell phone for a text message. The more secure in this case is the cell phone, which requires physical access (something you have) and but could be subject to a denial of service if wiped or stolen.

4. Why might the username/password still be of value to the attacker even if she can't use them to login to Facebook? (Hint: think about how users come up with passwords)
Because users have a habit of credential re-use. So, even if two-factor is causing difficulties in compromise for one account that doesn't mean that another account without two-factor doesn't have the same credentials. Likewise, even if one account is using a different or stronger password, that doesn't mean all user associated accounts are.

## Assignment
The following gifs and pngs provide proof of completing the steps listed in the assigment instructions. This ranged from the creation of the Tails VM to visiting specific .onion sites. Certain sites of Milestone 2.3 were not visited for the sake of avoiding inadvertanly viewing what might be considered content that is illegal. Although a grey area for many, without assurances that this possibility did not exist, I could not perform the small portion of that step in good conscience.
0. Challenge 0
![](https://github.com/dallens/CodepathWeek10SE/blob/master/w10_Ch0.png)

1. Challenge 1
![](https://github.com/dallens/CodepathWeek10SE/blob/master/w10_Ch01.png)
### 1.1
![](https://github.com/dallens/CodepathWeek10SE/blob/master/w10_Ch1-1.png)
### 1.2
![](https://github.com/dallens/CodepathWeek10SE/blob/master/w10_Ch1-2.gif)

2. Challenge 2
![](https://github.com/dallens/CodepathWeek10SE/blob/master/w10_Ch2-0.png)
### 2.1
![](https://github.com/dallens/CodepathWeek10SE/blob/master/w10_Ch2-1.gif)
### 2.2
![](https://github.com/dallens/CodepathWeek10SE/blob/master/w10_Ch2-2.gif)
### 2.3
![](https://github.com/dallens/CodepathWeek10SE/blob/master/w10_Ch2-3.gif)
### 2.4
![](https://github.com/dallens/CodepathWeek10SE/blob/master/w10_Ch2-4.gif)
### 2.5
![](https://github.com/dallens/CodepathWeek10SE/blob/master/w10_Ch2-5.gif)

## Assets

GIFs created with [LiceCap](http://www.cockos.com/licecap/).

## Notes


## License

    Copyright 2018

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
