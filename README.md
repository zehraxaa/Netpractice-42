_This project has been created as part of the 42 curriculum by aaydogdu_

## Description: What is NetPractice?

NetPractice is a project to understand the fundamentals of computer networking by training over 10 level exercises. These levels are designed in aim to solve different levels of small scale network architectures. This project involves understanding TCP/IP addressing, subnet masks, managing routing tables, and ensuring proper communication between various network devices such as hosts, routers, and switches.

## Instructions: How to download and run the NetPractice project?

### Download:
- Download the file ends with “.tgz” from intra, NetPractice project page.
- Extract the downloaded file into your preferred directory.
### Run:
- Open the directory in terminal and run “run.sh” executable. Type “./run.sh” on the command line
  ``` bash
  ./run.sh
  ```
  Manuel alternative; If the script fails, you can run a local Python serve. First run;
  ``` bash
  python3 -m http.server 49242
  ```
  You may change the port number, then in your web browser navigate to the URL in any port you have chosen.
  ``` bash
  http://localhost:49242
  ```
### Login:
 - In the opened page, enter your intra login for the training mode, or you can choose the evaluation mode. Training mode contains 10 levels of networking exercises (from 1 to 10); evaluation mode contains 5 levels of networking exercises (from 6 to 10) and appears 3 random exercises during this mode. And you are expected to solve these 3 random levels in 15 minutes.
### Getting Configurations and Submission:
 - Once you successfully pass the level, all goals happen to be “OK”. That means you passed and need to get your configuration. 
 - Click on “get my config” button and store them in a directory.
 - Later you complete all 10 levels correctly, you must submit your ten “*.json” (e.g. level1.json) config files with your own README.md file into the root of your git repository. 
 - Once you have 10 correctly named .json files and README.md file, you are ready to push your project (Don’t forget to check subject requirements before pushing).


## Resources: Networking Concepts Studied

During this project, the following networking concepts were studied and applied.

**TCP/IP Addressing:** Configuring IPv4 addresses for hosts and router interfaces.

**Subnet Masks:** Defining the boundaries of a network and understanding how many hosts a subnet can contain.

**Default Gateways:** Identifying the exit point for packets leaving a local network toward other networks or the internet.

**Routers and Switches:** Understanding how switches facilitate local traffic and how routers direct traffic between different subnets using routing tables.

**OSI Layers:** Analyzing how data flows through the Physical, Data Link, and Network layers

## External Sources:
I find useful these articles and playlists to understand networking and NetPractice project.

    https://www.kaspersky.com.tr/resource-center/definitions/what-is-an-ip-address
    https://berqnet.com/blog/tcp-ipv
    https://youtube.com/playlist?list=PLCXqoZAc8-tzD5N5oCyIyEcMg_NDs6o7C&si=qgR-DwN1axwKokSU
    https://bidb.itu.edu.tr/seyir-defteri/blog/2013/09/07/tcp-ip-protokolu

## AI Usage Description:
  In compliance with the project guidelines, AI was utilized as follows:
  
**Task 1: Concept Clarificatio:** AI was used to explain the mathematical logic behind CIDR notation and subnet mask calculations (e.g., explaining why a /26 mask covers 64 IP addresses).

**Task 2: Troubleshooting:** AI helped interpret the "packet not for me” and "correct IP reached but wrong host" error logs from the interface to identify misconfigured static routes.

**Task 3: Submission Preperation:** AI assisted in correcting grammer mistakes in this file and to ensure all mandatory sections from the PDF were included and covered.



