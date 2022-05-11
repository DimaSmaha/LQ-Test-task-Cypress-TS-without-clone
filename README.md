# LQ-Test-task-Cypress-TS
## Test task login and exploratory flow for cypress

### Automated tests of https://www.redmine.org/ website with using of Page Object pattern. Tests perfoms 
implementation of testcases for this website

#### Requirements: TS,NodeJS,Webdriver.io,Mocha,Cypress,TS

### Install software and check out the project
- Download and install Node.JS (at least 14.X)(https://nodejs.org/uk/)
- Install Visual Studio Code (https://code.visualstudio.com/)
- Make new folder and open it in VS code
- Open VS code terminal and enter(npx wdio config)
- Choose to install mocha and chromedriver
- Write (cd config) in VS terminal
- Install cypress in VS terminal using (npm install cypress --save-dev)
- Open package.json file and write to scripts("e2e": "cypress open") and save it
- Install node types (npm i --save-dev @types/node)
- Make tsconfig.json(https://docs.cypress.io/guides/tooling/typescript-support#Set-up-your-dev-environment) and add both mocha, and node to types 
- Rename index.js files to index.ts in cyress>plugins and cypress>support
- Enter (npm run e2e) to finish cypress setup
- Add project files to cypress>integration folder and enter (npm run e2e) start the project

#### Expected results: 
- Tests to be ran successfully

