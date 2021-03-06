[![Build Status](https://travis-ci.org/Dineshs91/devlog.svg?branch=master)](https://travis-ci.org/Dineshs91/devlog)
[![Join the chat at https://gitter.im/Dineshs91/devlog](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/Dineshs91/devlog?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## Devlog
### A log book for developers.

Devlog - Devlog is designed to assist you in keeping track of your notes, ideas etc in a simple yet intutive way. 
![Alt text](https://github.com/satish28/devlog/blob/master/Screenshot.png?raw=true "Sample screenshot") 

##### Key Features #####
**Index:**
Provides an index of all entries with Title and Date making it easy to find your notes.

![Alt text](https://github.com/satish28/devlog//blob/master/Loglist.png?raw=true "Index")

**Tags:**
Tags allow you to group similar log entries together. 
Ex: Say you are working on a project called "Devlog" and you have identifed additional features to add and issues. Tagging allows you to group similar ideas or notes and selecting the tag from the index displays only relevant tagged entries.

![Alt text](https://github.com/satish28/devlog/blob/master/Tagging.png?raw=true "Tagging")

**Restore or Permanently Delete Notes:**
Entries deleted in Devlog are not permanently deleted. The user has the ability to restore or delete the entries permanently using >> Options in Menu Bar.

![Alt text](https://github.com/satish28/devlog/blob/master/Restore&delete.png?raw=true "Tagging")

##### Devlog is built using: #####
*  [NW.js (Node-Webkit)](https://github.com/nwjs/nw.js/)
*  [ANGULARJS](https://angularjs.org/)
*  [NeDB (Node embedded databse)](https://github.com/louischatriot/nedb")

#####Testing#####
*  [Karma](http://karma-runner.github.io/0.12/index.html)
*  [Protractor](https://angular.github.io/protractor/#/)

#### Hacking
1. git clone 
2. npm install
3. npm start (To run the app from source) or npm start --remote-debugging 9222 (To use chrome devtools).
4. npm test (Complete testing. includes both unittests and e2e tests)

#### Other available commands
1. grunt jshint (Jshint)
2. npm run unittest (Run only the unittests)
3. npm run e2e (Run only e2e tests)

#### Todo
- [x] Add keyboard bindings.
- [x] Restore/Delete removed logs.
- [ ] During first time use, show an introduction log.
- [ ] Add an option to show all stats, like no. of logs etc.
- [ ] Import/Export logs.
- [ ] In app updates.
- [ ] Draggable logs. 

