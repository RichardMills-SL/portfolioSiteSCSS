# portfolioSiteSCSS
Portfolio Website by Brad Traversey on O'Reilly

Need to use npm to install 'node-sass' on terminal in VS Code, or standard Mac, Linux Terminal or Windows Command Prompt
<h3>Currently deployed at <a href="legbodyportfolio.ml"> legbodyportfolio.ml</a></h3>

<h2>Commands for node sass:</h2>
<p>Check version: 'npm --version'<br>
<p>If no version install npm.</p>

<p>install 'node-sass':
'npm install node-sass'</p>

<p>initialise:
npm init -y</p>

<p>'package.json' file should look like this:
<code> 
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
</code>
</p>
<p>then: 'npm run sass'</p>

<p>while running everytime you save it will compile the .sass folder in the sass folder to main.css.</p>

