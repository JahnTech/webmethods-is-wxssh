# WxSSH package for webMethods Integration Server

webMethods Integration Server package to execute commands via SSH on remote machines



## Development

- Prerequisite:
  - Use webMethods Service Designer (recommended)
  - For custom installations, yYou need "Local Service Development" installed 
    (located in Designer preferences at  "Software AG / Service Development / Local Service Development")
- Get sources
  - Via webMethods Designer (no separate Git installation needed)
    - Open "Java" perspective
	- Click "Import projects"
	- Select "Git / Projects from Git"
	- Select "Clone URI"
	- Paste Git URI from green "Clone or download" button above
	- Confirm defaults on all further dialogues and finish the import
  - Via command line (requires local Git installation)
    - Go into Designer workspace (e.g. `/home/john/workspace111`)
    - Clone Git repository into new directory `git clone https://github.com/JahnTech/webmethods-integrationserver-wxssh.git`
	- Import as existing project into workspace
- Activate package in Integration Server
	- If the "Service Development" perspective has not been active before you openend the "Java" perspective, you must quickly switch there and then directly back to "Java". This is needed to initialize the Local Service Development feature.
	- In the "Java" perspective right-click the project name and select "Move Project to IS Package"
	- Switch to the "Service Development" perspective and the WxSSH package should show up
	
	

______________________
These tools are provided as-is and without warranty or support. They do not constitute part of the webMethods product suite. Users are free to use, fork and modify them, subject to the license agreement. While JahnTech GmbH welcomes contributions, we cannot guarantee to include every contribution in the master project.

Contact us [via email](mailto:info@jahntech.com?subject=GitHub/webMethods) if you have any questions.
