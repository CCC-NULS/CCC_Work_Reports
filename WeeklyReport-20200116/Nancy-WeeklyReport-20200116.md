# Weekly Report
```
Time: 	2020.01.09 ~ 2020.01.16
Circle	: CCCc
Role:	Coder
Name: Nancy
```
## This week's summary

### CODING
- Updated and refactored all the nulsws-python code. Changed to
 match the PEP8 proposal doc. as suggested by Moshe. Some things should not be PEP8 
 compliant because they interact with Java components that don't insist on all-lowercase, etc. 
 I made code line length 90 instead of 79 since the trend is moving toward a longer line length and 
 our code contains long lines that need the extra space.
- Installed pyscaffold as recommended by Moshe. 
- Implemented using yapf, flake8 and venv. 
- Renamed and reorganized directories, and moved most variables into dictionaries for a 
cleaner namespace.
- Finished adding the config-parser library for user settings so that config files can be Nuls-style, ncf type 
files.
- Added http to the python project, although it's only http1.  Http2 is another whole decision on what libraries to use.
Made all the code PEP8 compliant

### CLOUD
- Got started using Berzeck's new west server, chain factory and the 
testnet.

### RESEARCH

- Finished researching http2 vs websockets for Berzeck.

### OTHER

- <b>TEAM</b> \- Attended Dave's weekly West meeting and the regular WeChat meeting.
- <b>ADMIN</b> \- Finished 2020 goals and plans and put on Trello.


## Next week's plan

- <b>CODING</b> - Work on adding the remainder of the 8 main Nulstar communication 
type methods to nulsws-python.
- <b>CLOUD</b> - Get the nulsws-python code running against the testnet. Install on 
the new west server too. Help team with demos if requested. 
- <b>DOCS</b> - Merge git devsite/dev into master for Kathy's documentation changes if
requested or necessary.
- <b>TEAM</b> - Attend meetings when requested.

## Work Problem Feedback

- None.
