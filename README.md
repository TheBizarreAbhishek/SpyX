# Disclaimer 
Any actions and or activities related to StealthPhisher is solely your responsibility. The misuse of this toolkit can result in criminal charges brought against the persons in question. The contributors will not be held responsible in the event any criminal charges be brought against any individuals misusing this toolkit to break the law.

This toolkit contains materials that can be potentially damaging or dangerous for social media. Refer to the laws in your province/country before accessing, using,or in any other way utilizing this in a wrong way.

This Tool is made for educational purposes only. Do not attempt to violate the law with anything contained here. If this is your intention, then Get the hell out of here!

It only demonstrates "how phishing works". You shall not misuse the information to gain unauthorized access to someones social media. However you may try out this at your own risk.

# Description 
A python phishing script for login phishing, image phishing, video phishing and many more

# Features 

 - Multi platform (Supports most linux)
 - 100+ templates
 - Concurrent 4 tunneling (Cloudflared and LocalXpose, LocalHostRun, Serveo)
 - OTP Support
 - Credentials mailing
 - Easy to use
 - Possible error diagnoser
 - Built-in masking of URL
 - Custom masking of URL
 - URL Shadowing
 - Portable file (Can be run from any directory)
 - Get IP Address and many other details along with login credentials

# Options
```
  -h, --help            show this help message and exit
  -p PORT, --port PORT  MaxPhisher's server port [Default : 8080]
  -t TYPE, --type TYPE  MaxPhisher's phishing type index [Default :
                        null]
  -o OPTION, --option OPTION
                        MaxPhisher's template index [ Default : null ]
  -T TUNNELER, --tunneler TUNNELER
                        Tunneler to be chosen while url shortening
                        [Default : Cloudflared]
  -r REGION, --region REGION
                        Region for loclx [Default: auto]
  -S SUBDOMAIN, --subdomain SUBDOMAIN
                        Subdomain for loclx [Pro Account]
                        (Default: null)
  -d DIRECTORY, --directory DIRECTORY
                        Directory where media files will be saved
                        [Default : /sdcard/Media]
  -f FEST, --fest FEST  Festival name for fest template [Default:
                        Birthday]
  -i YTID, --ytid YTID  Youtube video ID for yttv template [Default :
                        6hHmkInZkMQ (NASA Video)]
  -u URL, --url URL     Redirection url for ip-tracking or login
                        phishing [Default : null]
  -s DURATION, --duration DURATION
                        Media duration while capturing [Default :
                        5000(ms)]
  -m MODE, --mode MODE  Mode of MaxPhisher [Default: normal]
  -e TROUBLESHOOT, --troubleshoot TROUBLESHOOT
                        Troubleshoot a tunneler [Default: null]
  --nokey               Use localtunnel without ssh key [Default:
                        False]
  --noupdate            Skip update checking [Default : False]
```

# Usage 
1. Run the script
2. Choose a Website
3. Wait sometimes for setting up all
4. Send the generated link to victim
5. Wait for victim login. As soon as he/she logs in, credentials will be captured

# Installation
1. pkg install python3 -y
2. git clone https://github.com/TheBizarreAbhishek/StealthPhisher.git
3. python3 Stealthphisher.py

## Credits 
[PyPhisher](https://gitlab.com/KasRoudra/PyPhisher)
[Storm-Breaker](https://github.com/ultrasecurity/Storm-Breaker)
[Seeker](https://github.com/thewhiteh4t/seeker)
