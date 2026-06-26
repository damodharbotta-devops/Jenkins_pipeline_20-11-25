# Deploy a static application using Jenkins pipeline (Integrate with GIT, Maven, Nexus, Tomcat & SonarQube)

## Architecture :

## Code - CQA - Build - Test - Artifcat - Deploy - Post build actions (Email integration)

# Step:1 : Launch an 4 EC2 instance for jenkins, Tomcat, SonarQube & Nexus. 
<img width="1841" height="783" alt="Screenshot 2026-06-20 114201" src="https://github.com/user-attachments/assets/f046c195-1410-4147-8313-cc02f7a6e477" />

# 2. Install Git and all applications in respective servers.

<img width="1797" height="689" alt="Screenshot 2026-06-20 114221" src="https://github.com/user-attachments/assets/37db2ec8-a474-496f-9e11-ef1ae1168cac" />
<img width="1892" height="298" alt="Screenshot 2026-06-20 114540" src="https://github.com/user-attachments/assets/c89af454-956a-4c3b-80ba-499579937d6e" />
<img width="1531" height="566" alt="Screenshot 2026-06-20 115255" src="https://github.com/user-attachments/assets/3c28b12d-f356-47b7-9193-7106ab01379e" />
<img width="1669" height="681" alt="Screenshot 2026-06-20 145339" src="https://github.com/user-attachments/assets/1961d520-a57f-4721-93c4-4c9cbc961bf0" />
<img width="1409" height="629" alt="Screenshot 2026-06-20 154204" src="https://github.com/user-attachments/assets/b43a2685-d1db-4ecc-a84d-39a37b09bf47" />

# 3. Access the all the Jenkins, Tomcat, Nexus & SonarQube dashboards with Public Ip address:port number.

<img width="1897" height="925" alt="Screenshot 2026-06-20 150842" src="https://github.com/user-attachments/assets/39dd1195-4d6e-4967-8b05-04d05cdc7d15" />
<img width="1889" height="941" alt="Screenshot 2026-06-20 150858" src="https://github.com/user-attachments/assets/e9631212-9064-4007-8bc4-09e517b1b762" />
<img width="1914" height="926" alt="Screenshot 2026-06-20 150908" src="https://github.com/user-attachments/assets/d78adecb-3434-423d-b773-b738ab6d692d" />
<img width="1898" height="1010" alt="Screenshot 2026-06-20 154421" src="https://github.com/user-attachments/assets/f965f66b-4322-4588-bd4b-0216b8565569" />

# 4. Install the required plugins and integrate with Jenkins.

# Plugins:
1. Pipeline stage View
2. SonarQube Scanner
3. Nexus Artifact Uploader
4. Deplot to Container
5. Email Extension Template

<img width="1917" height="574" alt="Screenshot 2026-06-20 151428" src="https://github.com/user-attachments/assets/a184bd36-7a65-4453-9093-b1e8baefdad0" />
<img width="1862" height="822" alt="Screenshot 2026-06-20 155204" src="https://github.com/user-attachments/assets/75d3e4fb-0bdb-4435-8dde-34f36c14d0db" />
<img width="1902" height="578" alt="Screenshot 2026-06-20 165922" src="https://github.com/user-attachments/assets/7c512b09-2b54-4e40-aed9-f96f225459e9" />
<img width="1919" height="506" alt="Screenshot 2026-06-20 182410" src="https://github.com/user-attachments/assets/c340372e-7ab1-4c5e-ac6f-7ec0fadaff3a" />
<img width="1917" height="911" alt="Screenshot 2026-06-20 195439" src="https://github.com/user-attachments/assets/9cf30fa1-cc86-4cee-9ee8-f58b2d4f6659" />

# i) Install Git in Jenkins server and write the pipeline syntax for stage 1 code.
# ii) In stage 2: Code Quality Analysis: write the pipe line syantax and integrate with Jenkins.
# iii) In stage 3: write the pipeline syntax to Build the code and integrate maven with jenkins.
# iv) In sonarQube dashboard check the code status.

<img width="1887" height="1005" alt="Screenshot 2026-06-20 170113" src="https://github.com/user-attachments/assets/47120e58-1238-4700-ab13-7bf9bfcc47d6" />
<img width="1916" height="877" alt="Screenshot 2026-06-20 155802" src="https://github.com/user-attachments/assets/1e177ece-d99d-47fc-8dcc-812efaf4a8cd" />
<img width="1903" height="1008" alt="Screenshot 2026-06-20 155840" src="https://github.com/user-attachments/assets/1d84c4d9-f30e-41d5-b889-39d3d3884ef9" />
<img width="1779" height="701" alt="Screenshot 2026-06-20 155043" src="https://github.com/user-attachments/assets/3b7f4b9a-79f3-4a2a-851c-b1438300219e" />
<img width="1918" height="1005" alt="Screenshot 2026-06-20 163238" src="https://github.com/user-attachments/assets/6a44303d-ae31-4229-ad27-20108073d43e" />

# iv) Write pipeline syntax for Nexus and integrate Nexus with Jenkins.
# Create repo in nexus dahboard and see the nexus artifacts in the repo
<img width="1916" height="1021" alt="Screenshot 2026-06-20 181127" src="https://github.com/user-attachments/assets/20c4b1a1-081d-41e3-9a52-366e95cf127b" />
<img width="1919" height="1031" alt="Screenshot 2026-06-20 181141" src="https://github.com/user-attachments/assets/919d89c1-6a1c-4829-8373-e858edd3826d" />
<img width="1919" height="995" alt="Screenshot 2026-06-20 182230" src="https://github.com/user-attachments/assets/b5ade58e-8b7c-48ab-8b0d-53d435dcc456" />

# v) In deploy stage, write the pipeline syntax for tomcat and integrate tomcat with Jenkins
# Deploy the application in tomcat server

<img width="1905" height="1022" alt="Screenshot 2026-06-20 195404" src="https://github.com/user-attachments/assets/fb83c296-cfde-4a8c-b8a9-bc478b3520b4" />
<img width="1920" height="1080" alt="Screenshot (101)" src="https://github.com/user-attachments/assets/6294bee7-61c6-4d23-bdda-f567b41c1603" />
<img width="1920" height="1080" alt="Screenshot (102)" src="https://github.com/user-attachments/assets/89c1c8cf-9ded-4c2c-8643-d5689d8cf2a1" />
<img width="1898" height="1018" alt="Screenshot 2026-06-20 193605" src="https://github.com/user-attachments/assets/74ab3607-a685-44a6-b312-fcc76a69d8fe" />


# Vi) Post build actions Email integration: Integrate Email with Jenkins to get updates of build actions
<img width="1919" height="745" alt="Screenshot 2026-06-20 200527" src="https://github.com/user-attachments/assets/aadbba26-23a4-4cf6-b91c-094f9cc03ab4" />

