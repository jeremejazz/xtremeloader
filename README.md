# XtremeLoader

Application for LoadXtreme quick access to online transactions such as online loading, transfer, etc.

#### Requirements:

- npm
- grunt

### Installation

#### Install tools and dependencies

`
npm install
`

`
npm install -g grunt-cli
`
#### Build
This the build files are already included. For changes made though you can run

`grunt`

#### Running
You can run the site by simply using the command

`
grunt serve
`

This will automatically open your default browser using **grunt-http-server**
#### Screenshots
![alt text](screenshots/load.png "Load Page")


## Notes:
(just some personal notes/reminds.  forget about this part. will be using trello later)


Navigation

- Pages should have a class called navigation_panel
- Navigation button should have toggle_panel class


Todo
- ~~UX change. Split pages into 2 parts to avoid scrolling down. Use next button instead, *like a wizard Harry!*.~~
- ~~"Your request has been queued. Click here to track request" // remove click here. Truncate after dot~~
- list should clear on selection of new category
- *validation for blank entries, email format (better in realtime for formats),*
- Ajax loader for all ajax events
  -categories (done)
- reset function  
- Navigation panel links
  - Settings page
    - Themes
    - Profiles
  - Help
  - About  
  - Report a Bug

- Wizard for first run, ask user information. Also add option to skip
- class for ajax
- class for sms send (for future version)
- Based on interface. even though js doesnt have interfaces
