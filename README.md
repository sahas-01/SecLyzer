# Flipkart GRiD 4.0 - Information Security Challenge

<br>

# 🎡 Problem Statement
#### Open Source Software (OSS) Security Inspector.<br>
Open source software is an integral part of every tech product. There are amazing contributors who actively maintain their repositories. However, every coin has two sides. All OSS repositories may not be maintained properly, because of which, vulnerabilities may get introduced with time. Whereas, some OSS repos could be created by attackers themselves to trick the users. We need an OSS inspector to solve this problem. This tool will help us to identify the genuineness of the repos and perform a security health check.

## 💎 Brief description about the project
We have built an application that can:- <br>
 - Analyze Github, github, pypi and npm repos. <br>
 - Perform the scan with repository link. <br>
 - Provides the rating for the repository based upon <b>OWASP Top 10 vulnerabilities</b> along with few other vulnerabilities. <br>
 - Display snippet of the code having vulnerabilities. <br>
 - There might be some vulnerabilities that may be False positives and We can manually mark those vulnerabilites as false positives or remove them from the detected vulnerabilities. <br>
 
## 👩🏻‍💻 Tech Stack
 - HTML/CSS
 - Bootstrap
 - Javascript
 - Python
 - Flask
 - PostgreSQL
 - Ginger Template 

## 🎬 Getting Started (Linux/Mac)
<a href="https://adamtheautomator.com/install-postgresql-on-a-ubuntu/">Install Postgres</a> and configure `SQLALCHEMY_DATABASE_URI` in `SecLyzer/settings.py`.<br>Format `postgresql://<User>:<Password>@127.0.0.1/<Database_Name>`

#### Steps to set up SecLyzer Locally
```
git clone https://github.com/parikshit3000/SecLyzer.git
cd SecLyzer
python3 -m venv venv
source venv/bin/activate
pip install -r packages.txt
python3 global_functions.py initialize-db # Run once to generate database schema
```

##### To run SecLyzer
`./run.sh`

This will run SecLyzer Web application at `http://127.0.0.1:9090`

## ✨ Future Scope
 - Suggestions for removing the vulnerabilites from the code.
 
## 👫 Contributors 
* [Parikshit Juneja](https://github.com/parikshit3000)
* [Pranav Desai](https://github.com/pranavvdesai)
* [Garv Tandon](https://github.com/garvsgit)

Team Name:- `Code Smashers`
