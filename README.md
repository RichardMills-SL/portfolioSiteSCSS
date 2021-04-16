# portfolioSiteSCSS
Portfolio Website by Brad Traversey on O'Reilly

Need to use npm to install 'node-sass' on terminal in VS Code, or standard Mac, Linux Terminal or Windows Command Prompt

<h2>Commands:</h2>
Check version:
'npm --version'
If no version install npm.

install 'node-sass':
'npm install node-sass'

initialise:
npm init -y

'package.json' file should look like this:
{
  "name": "PortfolioWebsite",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "sass": "node-sass -w scss/ -o dist/css/ --recursive"
  },
  "keywords": [],
  "author": "",
  "license": "ISC",
  "devDependencies": {
    "node-sass": "^5.0.0"
  }
}

then:
'npm run sass'

while running everytime you save it will compile the .sass folder in the sass folder to main.css.

