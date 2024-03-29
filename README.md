# SSH-Honeypot Analyzer
> Honeypot: Honeypots are decoy servers or systems set up to gather information regarding an attacker or intruder into a system. They are designed to look vulnerable to attack, but once an intruder gains access to the system all of their actions are controlled and monitored.
 
 This whole thing was made possible by: [droberson](https://github.com/droberson/ssh-honeypot) and [roxdog](https://github.com/olanga)

## About
This is simply a `.log` analyzer for files generated by the repository mentioned above

## Features
- Request distribution over the last days
- Request distribution over the last hours
- Most used passwords

## Requests
<div align="center">How many requests there where
 <img src=https://github.com/NotNanook/SSH-Honeypot/blob/main/images/requestDistributionGH.jpg>
 How they where distributed
 <img src=https://github.com/NotNanook/SSH-Honeypot/blob/main/images/requestOverDaysGH.jpg>
</div>


## Passwords
Here are the Top 5 most tried passwords

| Password      | Amount of tries |
| :-------------: |:-------------:|
| 123456    | 1246 |
| 1         | 532 |
| 123 | 519 |
| password | 461 |
| 1234 | 373 |

## Todo
- Geolocation based on IP
